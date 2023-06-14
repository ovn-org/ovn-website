+++
date = 2023-06-14T09:30:35-04:00
title = "Release 23.06.0"
+++

In addition to bug fixes, the 23.06.0 release of OVN contains a multitude of
new features.

### New Features
- Logical switch port's options:arp\_proxy has been expanded to support IPv6, configurable MAC addresses, and CIDRs.
- A new "ct\_flush" option has been added for load balancers to flush connection tracking entries due to certain load balancer updates.
- ovn-ic now has configurable OVSDB probe intervals.
- ovn-controller-vtep now has configurable OVSDB probe intervals.
- ovn-controller-vtep has new ovn-appctl commands "sb-connection-status" and "vtep-connection-status".
- ovn-ic has new ovn-appctl commands "nb-connection-status", "sb-connection-status", "ic-nb-connection-status", and "ic-sb-connection-status".
- logical switches now have an other\_config:broadcast-arps-to-all-routers option.
- IPv6 iPXE support for "bootfile\_name" and "bootfile\_name\_alt" has been added for DHCPv6.
- Mirroring support has been expanded to be able to use a local OVS port as a target.
- Mirroring has been updated to allow "both" as a direction on the "filter" field.
- ovn-ic-nbctl, ovn-ic-sbctl, ovn-nbctl, and ovn-sbctl's default probe intervals have been increased from 5000 ms to 120000 ms.
- QoS no longer directly configures linux-htb qdiscs. Instead, OVN configures QoS via OVS.
- Support for tiered hierarchical ACLs. ACLs have a new "pass" verdict to move to the next
