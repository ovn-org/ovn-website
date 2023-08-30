+++
title = "Changelog v21.12.1"
[_build]
  list = 'never'
+++

### Changes from v21.12.0 to v21.12.1

- [a1001ce7](https://github.com/ovn-org/ovn/commit/a1001ce71dd24da6c2412e403db4f423ce2ba2bb) Set release date for 21.12.1.
- [21697035](https://github.com/ovn-org/ovn/commit/2169703529f47b50e0871e64fa6921170002cd51) controller: reconfigure ovs meters for ovn meters
- [091f1b5a](https://github.com/ovn-org/ovn/commit/091f1b5a31e4cef212d2c7f92b6371a0c97d1cf6) branch-21.12: Fix the compilation error.
- [77f75121](https://github.com/ovn-org/ovn/commit/77f7512157f863e481ba9f8f41f3feece63d43f6) northd: Support the option to apply from-lport ACLs after load balancer.
- [c96bf2fa](https://github.com/ovn-org/ovn/commit/c96bf2fa983e7c849e9f094e4e5edcc8b4312700) ovs: Bump submodule to stable branch-2.17.
- [11645b21](https://github.com/ovn-org/ovn/commit/11645b21b4ed8a22220b5a635b2a3217f68904bf) ci: ovn-kubernetes: Bump kubernetes version to v1.23.3.
- [4331e12f](https://github.com/ovn-org/ovn/commit/4331e12f0feff7c19036ab32b1680f11d00fc919) ci: ovn-kubernetes: Generate DB model based on current OVN tree.
- [5c6f3c6c](https://github.com/ovn-org/ovn/commit/5c6f3c6c9aae97b87f4d968251e7dfdd5f299e99) northd: introduce exclude-lb-vips-from-garp option for lsp
- [a136a82f](https://github.com/ovn-org/ovn/commit/a136a82fcb5dc90700f2059dac1994232d62d242) ovn-northd: Don't log transaction failures on standby instances.
- [3c727ff4](https://github.com/ovn-org/ovn/commit/3c727ff4d03618154fef556f40b6e5c239b67250) lflow: Fix conjunction ID allocation problem with DP groups.
- [9038ab66](https://github.com/ovn-org/ovn/commit/9038ab66fcee57bdfff4b39b318ed3f89cd35400) introduce rdnss, dnssl and route_info opt in put_nd_ra_opts action
- [3b78224b](https://github.com/ovn-org/ovn/commit/3b78224bee7eccd4f9e3dd125d5813821069b189) Set additional header in DNS message explicitly
- [db51c2ad](https://github.com/ovn-org/ovn/commit/db51c2ad942af91775f5111ba4d57193ed8ddb48) northd.c: Fix nbcfg timestamp - use time_wall_msec instead of time_msec.
- [ae1318c7](https://github.com/ovn-org/ovn/commit/ae1318c742f707f811779cd84cbe4cdc889f2362) ovn-parallel-hmap: Fix NUMA and core detection.
- [59a42559](https://github.com/ovn-org/ovn/commit/59a42559e0cd83b269c214a43fed858cd87284e2) ci: Install wheel before installing any other python packages.
- [5d05cd2d](https://github.com/ovn-org/ovn/commit/5d05cd2d93689ea8b0e97e8178e318e043ca0257) pinctrl: Avoid false positive out of bounds warning.
- [17c22d4a](https://github.com/ovn-org/ovn/commit/17c22d4a43a493558572ff1fde728b98e0fef1bd) pinctrl: Fix potential stack overflow in pinctrl_compose_ipv6().
- [18f9509e](https://github.com/ovn-org/ovn/commit/18f9509e3e2c6c319299578c70cd632faa69c02b) ovn-northd: Enable change tracking for all SB tables.
- [0bce1553](https://github.com/ovn-org/ovn/commit/0bce1553f4231d76b37a48642269e3e8fd3a8207) vtep: set is-vtep to chassis's other_config if absent
- [2bbef142](https://github.com/ovn-org/ovn/commit/2bbef142105d93bd6b492d4c80a84fc1e599d66f) northd: Remove potential duplicates in SB Load_Balancer table.
- [32f997b1](https://github.com/ovn-org/ovn/commit/32f997b13a58f5e32fa4a65828a2cb1a113039ae) Add isc-dhcp-server to github workload
- [59d974be](https://github.com/ovn-org/ovn/commit/59d974be1d11e137e68cbeab07f1d31b1a24d9ca) test: replace dibbler with dhcpd
- [1eae4391](https://github.com/ovn-org/ovn/commit/1eae43916edde2443578f477560ea03c0c22dec7) northd: fix IPv6-PD with northd IP rework
- [290523cd](https://github.com/ovn-org/ovn/commit/290523cdfadc5cb401939cc21c1f8de66a6b79b2) pinctrl: Avoid misaligned access to ovs_ra_msg.
- [2280d3a3](https://github.com/ovn-org/ovn/commit/2280d3a3f63e026657564f34793b9143323afaf6) pinctrl: Avoid misaligned access to controller_event_opt_header.
- [ca764d60](https://github.com/ovn-org/ovn/commit/ca764d60c6cfd4e7121b15faf6ca3a026928da4e) pinctrl: Ensure packet headers are properly aligned for ICMP errors.
- [67829e14](https://github.com/ovn-org/ovn/commit/67829e142dcc71b1f8e4f01aab9e73333420a76f) pinctrl: Ensure aligned accesses when processing DNS.
- [b5083fdb](https://github.com/ovn-org/ovn/commit/b5083fdb4dce839fe70ce5e1c059f11c917105f4) pinctrl: Ensure no misaligned accesses for SCTP packets.
- [31e93346](https://github.com/ovn-org/ovn/commit/31e933469d862915b8c83131f72728fe32ecac51) pinctrl: Ensure proper alignment when using pinctrl_compose_ipv*().
- [627b25bd](https://github.com/ovn-org/ovn/commit/627b25bd14085a78f1f9611f2a218ce639515e26) physical: Add remote parent ports to OFTABLE_REMOTE_OUTPUT flows.
- [9c67f93b](https://github.com/ovn-org/ovn/commit/9c67f93b92d9864ac0e06dd3d96e8172441343c3) Prepare for 21.12.1.