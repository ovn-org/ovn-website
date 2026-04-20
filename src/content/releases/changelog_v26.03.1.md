+++
title = "Changelog v26.03.1"
[_build]
  list = 'never'
+++

### Changes from v26.03.0 to v26.03.1

- [161f9b02](https://github.com/ovn-org/ovn/commit/161f9b02c51a1fce2cfbe82b7616aa35ee23aae8) Set release date for 26.03.1.
- [4892929e](https://github.com/ovn-org/ovn/commit/4892929ea15f3409751a4309635a6522c2ea5b0b) pinctrl: Make sure the BFD packet contains correct amount of data.
- [78f6ce61](https://github.com/ovn-org/ovn/commit/78f6ce612403d6343f1e3782cbfff691d411dee4) pinctrl: Unify handling of DHCPv6 options.
- [9d674c68](https://github.com/ovn-org/ovn/commit/9d674c684a56aef12c53b1e4596b6eded23a0402) pinctrl: Limit the IP packet size to buffer size for ICMP Need Frag.
- [e8dc4202](https://github.com/ovn-org/ovn/commit/e8dc420206d26c4629597b26739278a6772450d4) northd: Skip conntrack for EVPN remote VTEP traffic.
- [58f8de11](https://github.com/ovn-org/ovn/commit/58f8de11467dc0cc293af9b4d8603ab08fdbb0a8) northd: Fix ls_stateful_record_set_acls() not called in I-P handlers.
- [6a1395f5](https://github.com/ovn-org/ovn/commit/6a1395f5486ffd793aa4aeb4ae1c72bc34af97c5) northd: Remove redundant init_mcast_info_for_datapath() call.
- [639b3a3e](https://github.com/ovn-org/ovn/commit/639b3a3eca6342997cb7a2fc25c5941a99478341) northd: Fix other_config init in incremental LS processing.
- [7d24bd5a](https://github.com/ovn-org/ovn/commit/7d24bd5ae4e01719b295d6756d7ead42b6c4d559) controller: Make sure we free the route_data during change check.
- [4966254e](https://github.com/ovn-org/ovn/commit/4966254eea31d4e8bc1c15efb7c1c91abe2c4de5) controller: Add missing neighbor_table_notify_destroy call.
- [0d49036f](https://github.com/ovn-org/ovn/commit/0d49036fc923b9cd7c875508377b6016a183192e) northd: Don't forward IP multicast to routers without IGMP relay.
- [35ef3e3b](https://github.com/ovn-org/ovn/commit/35ef3e3b3699f3ddfbb34871e47d5a9d2673b830) tests: Stabilize localnet_learn_fdb packet-in count.
- [4feb2d54](https://github.com/ovn-org/ovn/commit/4feb2d54475b2c47aafe58f48b871477bd219298) northd: Fix requested-tnl-key not reassigned after conflict resolved by deletion.
- [1a10fe06](https://github.com/ovn-org/ovn/commit/1a10fe06d3d4438dcec893e4132c876fe1c54b67) controller: Fix bfd up too early after unexpected reboot.
- [725acb2d](https://github.com/ovn-org/ovn/commit/725acb2db5f2179ad28d8adf592361715f5c6e97) ofctrl: Look for duplicated conjunctions directly in the ofpacts.
- [a58e629b](https://github.com/ovn-org/ovn/commit/a58e629b26884af3f13c9e6a488d44d045529b10) ofctrl: Fix removing wrong conjunction during the duplicate check.
- [aff575ad](https://github.com/ovn-org/ovn/commit/aff575ad99dc3ee8240bbfbd186471c94b1d96f2) ofctrl: Count the number of referenced flows with address sets.
- [276eea65](https://github.com/ovn-org/ovn/commit/276eea658ea7e6347753d6f5136af4efa57e2560) ofctrl: Use hash map lookup for duplicate references check.
- [dbf38a05](https://github.com/ovn-org/ovn/commit/dbf38a05b862bef6293241587e5e4b60945aaf3d) ofctrl: Track Sb flow references in a hash map.
- [86b0fdfd](https://github.com/ovn-org/ovn/commit/86b0fdfdfebd4b014efa807cb8819250e7b800be) northd: Fix L3 EVPN when remote VTEP is not L2 adjacent.
- [77bd94ed](https://github.com/ovn-org/ovn/commit/77bd94ed1d49233b50994a5c515ea5dc26e6afa0) northd: Learned route use nexthop address family for outport IP selection.
- [9cc3aa21](https://github.com/ovn-org/ovn/commit/9cc3aa2183694b4c5ca9b85b814f50603f66921f) northd: Use nexthop address family for ECMP symmetric reply flows.
- [b449425d](https://github.com/ovn-org/ovn/commit/b449425d76f780458eab6c45a7a18230a8452c8b) northd: Use nexthop address family in find_static_route_outport.
- [ba3683c0](https://github.com/ovn-org/ovn/commit/ba3683c0de5c400040185a6449128547b2dbeaf5) controller: Fix an assertion failure with multiple mirror types.
- [e080e941](https://github.com/ovn-org/ovn/commit/e080e941e715b5718f1bb31512d52829176523be) Prepare for 26.03.1.