+++
date = 2021-03-15T08:53:48-05:00
title = "Release 21.03.0"
+++

In addition to bug fixes, the 21.03.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- When using the "reject" ACL verdict with SCTP, OVN now responds with an SCTP ABORT.
- OVN now supports "memory/show" via ovn-appct similar to OVS.
- OVN now supports using BFD on static routes to test liveness. See ovn-nb documentation for more details.
- Various ovn-nbctl enhancements
    - lr-route-list gives a BFD report
	- lr-route-list gives ECMP and ECMP symmetric reply information
	- lr-lb-add option now has an --event option to enable controller events for empty backends.
	- lr-route-add now has a --bfd option to enable BFD.
	- lb-add has a --reject option to automatically reject packets sent to VIPs with no backends.
- ovn-ic now has a systemd-unit
- Load balancers have a "hairpin\_snat\_ip" option. See ovn-nb documentation for more information.
- RBAC additions:
    - Chassis\_private external\_ids
	- IGMP\_Grup table
	- Controller\_Event table
	- FDP table
- MAC learning support has been added.
- DCHP Options 44 and 45 (NB Name Server, NB Node Type) are now supported.
- Logical router policies now support ECMP.
- lflow cache now has a lflow-cache/show-stats command accessible via ovn-appctl
- Support for building Debian packages has been re-added.

### Performance Enhancements
- Partial set and partial map updates are used in place of full set replacement in OVSDB operations. In several cases this greatly reduces the size of messages transmitted during OVSDB operations.
- Rather than pre-programming all possible load balancer hairpin flows, we now use the "learn" action in OVS. This has the potential to greatly reduce the number of flows installed by OVN.
- Several checks of conntrack fields have been removed. This improves chances of flows being offloadable in certain scenarios.
