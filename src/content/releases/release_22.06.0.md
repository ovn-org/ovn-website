+++
date = 2022-06-03T08:53:48-05:00
title = "Release 22.06.0"
+++

In addition to bug fixes, the 22.06.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- Many features that made use of ct\_label now use ct\_mark. This allows for easier hardware offloading.
- NAT may now be configured on routers with multiple distributed gateway ports.
- MAC bindings may now be configured via the northbound database.
- "requested-chassis" now accepts a comma-separated list to allow for a port to be bound to multiple chassis.
- ACLs may now be configured to drop by default instead of allowing by default.
- QOS may now be configured to allow for a minimum bandwidth guarantee.
- An option has been added to regulate whether load balancer VIPs have ARP responder flows added by default.
- ovn-northd parallelization options have been overhauled.
- The "next-server" field can now be sent in DHCP replies sent by OVN.

### Performance Enhancements
- Flow installation has been modified to minimize dataplan downstime during an upgrade/restart.
- load balancer gateway router flows have been optimized, bringing ovn-northd loop execution down.
- Port security flows are calculated in ovn-controller instad of ovn-northd now. This results in both ovn-northd and ovn-controller running more efficiently.

