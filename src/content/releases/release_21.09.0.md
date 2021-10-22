+++
date = 2021-10-21T08:53:48-05:00
title = "Release 21.09.0"
+++

In addition to bug fixes, the 21.09.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- OVN can now detect datapath features in OVS using the "Datapath" table in OVS. This is used to detect if all-zero SNAT is available.
- DHCP now supports option 12 (hostname).
- A limitation has been removed that now allows the full TCP/UDP port range (1-65535) rather than only half the range (1-32767) for Service Monitors.
- Proxy ARP support has been added for Logical Switch ports of type "router".
- An "--add-route" option is available for the "ovn-nbctl lr-nat-add" and "ovn-nbctl lr-lb-add" commands. This automatically creates static routes to the VIP or external IP from connected routers and adds ARP/ND resolution flows for these IP addresses.
- Many new stopwatches have been added to ovn-northd and ovn-controller for more fine-tuned debugging of execution times.
- A new "ovn-sbctl count-flows" command has been added in order to retrieve the number of logical flows more quickly.
- Control Plane Protection (CoPP) has been added. 
- PMTU discovery has been added for incoming traffic from outside the OVN cluster.
- Memory usage statistics can be gathered from ovn-northd.
- Distributed routers may now have more than one gateway port.
- ACLs can now be given labels so that it can be detected which ACL was responsible for allowing traffic.
- In addition to external\_ids:iface-id, a new optional external\_ids:iface-id-ver option has been added for OVS Interfaces to allow for more control over when ports are bound.
- Static routes with no nexthop may be configured.
- OVN now stores the timestamp when a port is bound. It is stored in external\_ids:ovn-installed-ts in the OVS Interface table.


### Performance Enhancements
Generally speaking, performance was a major focus for the development of OVN 21.09.0.
- Logical flows for DNAT have been reorganized to avoid unnecessary recirculations.
- IPv6 prefix delegation and router advertisements are now processed incrementally in ovn-controller.
- Memory is trimmed when the logical flow cache in ovn-controller reduces significantly in size.
- Load balancer processing has been significantly improved:
    - Southbound Datapath\_Binding records have been decoupled from Load\_Balancers. This change reduced ovn-northd execution time of a heavy load balancer test case by about 80%.
    - Load balancer defrag flows are now processed once for all routers. This change reduced ovn-northd execution time of a heavy load balancer test case by about 10%.
    - SNAT hairpin flows now use conjunctive matches. Previously, the number of flows was proportional to the number of Load Balancer VIPs x the number of datapaths. Now it is proportional to the number of Load Balancer VIPs + the number of datapaths. In a test with heavy load balancer use, this reduced the execution time of ovn-controller by 26%, reduced the number of OpenFlow flows by 72%, and reduced the memory used by 72%.
    - Some logical flow calculations were optimized, resulting in a 25% reduction in computation time in ovn-northd.
- Non-local logical flows can be skipped by ovn-controller befor parsing. This change reduced ovn-controller execution time by 70% with the lflow cache disabled. It reduced ovn-controller execution time by 65% and reduced memory usaged by 80% when the lflow cache is enabled.
- OVSDB client API improvements have been added:
    - Reconnecting to a database resets the backoff counter, meaning that reconnection typically happens much quicker, rather than a minimum of 8 seconds.
    - Optimizations have been made for JSON string serialization.
    - The client side of the ovsdb-data module has been optimized.
- ARP flood flows for known unreachable IPs have been broken into multiple logical flows instead of being combined into one. This reduced OpenFlow installation time by about 98% for cases with many unreachable IP addresses.
- Physical flows and Connection Tracking zones have enhanced incremental processing logic, allowing for fewer full recomputes in ovn-controller when physical changes occur.
- A change to reduce the number of flows for cases where logical switches are pinned to a single chassis was added. This reduced the number of OpenFlow flows per node by 70%, reduced ovn-controller memory by 80%, reduced ovn-controller recompute time by 90%, and reduced ovn-controller restart time by 90%.
- Pipelines in ovn-northd are represented as digits instead of strings, resulting in a savings of 1-3.5% in processing time.
- Logical datapath groups are now enabled by default. These were introduced in OVN 21.03.0 but were not enabled by default. Enabling them allows for repeated logical flows to be stored only once in the southbound database.
- Parallelized ovn-northd was optimized to work better with datapath groups, resulting in a speedup of about 10%.
- ovn-northd ddlog received a numerous improvements to its processing, resulting in memory consumption being reduced by as much as 85% and reducing execution time by a significant amount too.

### Documentation

Distribution documentation (aka man pages) specific to this release is
[available here](https://www.ovn.org/support/dist-docs-branch-21.09/).
