+++
date = 2022-10-03T08:53:48-05:00
title = "Release 22.09.0"
+++

In addition to bug fixes, the 22.09.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- Load balancers attached to logical routers have the option to automatically be applied to connected logical switches as well.
- When multiple requested chassis are used for a switch port, a RARP activation strategy has been implemented to allow for automatic switchover between the chassis.
- An IPsec option has been added to force NAT-T encapsulation.
- ovn-ctl can now accept arbitrary args, which can be passed along to the daemons it starts.
- An aging mechanism has been added to MAC\_Bindings so that they are removed after a certain amount of idleness.

### Performance Enhancements
- Logical datapath groups are no longer an option to be enabled. Instead, they are always used, resulting in performance improvements without having to set an option.
- Datapath groups are used for southbound load balancers, resulting in improved southbound database and ovn-northd performance, and decreased memory usage.
- Several improvements have been made to avoid downtime of the dataplane during upgrades and restarts.
- ovn-northd will attempt to accumulate more database updates before blindly processing the first one it sees.
- Changes to the data structures used in ovn-northd for datapath groups resulted in a near 3x speedup of ovn-northd, and nearly halving the memory used.
