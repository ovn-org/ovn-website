+++
date = 2020-12-17T08:53:48-05:00
title = "Release 20.12.0"
+++

In addition to numerous bug fixes, the 20.12.0 release of OVN contains a mix of new features and performance improvements.

### New Features

- Add support for DHCP RENEW/REBIND for IPv6 prefix delegation (RFC 3633).
- DHCP iPXE support has been added.
- A new vlan-passthru option has been added to logical switches to allow vlan-tagged incoming traffic.
- DHCP option 28 (broadcast address) support has been added.
- The conntrack zone used by a gateway router for SNAT can now be explicitly configured.
- The nb\_cfg value is now propagated to the OVS database.
- It is possible to pin ovn-northd or ovn-controller to a specific version. This can allow for less downtime during upgrades if the central components are updated before the ovn-controllers in a cluster.
- Support for "fair" meters, which allows for multiple ACL logs to use the same meter while being rate-limited independently.

### Performance Enhancements

- "reject" ACLs have been reduced from generating 4 logical flows to generating 1.
- MAC bindings are updated for directly-connected logical routers, saving the need for unnecessary ARPs/NDs.
- The number of flows required for hairpin traffic to load balancers has been reduced.
- ovn-northd can now group logical flows that are shared between multiple datapaths using datapath groups. This has been shown to dramatically reduce the number of logical flows in the southbound database in large deployments. The option is disabled by default but likely will be switched to be enabled by default in a later release.
- Some OVSDB operations have been updated to use partial map updates, reducing the size of the data being sent and processed in a transaction.
