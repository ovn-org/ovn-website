+++
title = "Changelog v23.06.4"
[_build]
  list = 'never'
+++

### Changes from v23.06.3 to v23.06.4

- [d15f82db](https://github.com/ovn-org/ovn/commit/d15f82dbd20bb5fc304f395b20860bcd695006d3) Set release date for 23.06.4.
- [920339ec](https://github.com/ovn-org/ovn/commit/920339ec76a7800455feeb731efa18b6f5ed896b) controller: Fix an issue wrt cleanup of stale patch port.
- [88f8d8f2](https://github.com/ovn-org/ovn/commit/88f8d8f2cbbd472fbdae0d89703d5578af4fad33) ci: Fix OPTS not being passed to OSX builds.
- [f3021c1c](https://github.com/ovn-org/ovn/commit/f3021c1c3e016e11bcadf4e32fde63e4ceb2d5d0) ovn-nbctl: Document "--portrange" in the manpage.
- [8b961c96](https://github.com/ovn-org/ovn/commit/8b961c966a45ccb14c1fa760196b12ff47fd6022) rbac: Only allow relevant chassis to update BFD.
- [ff7b7373](https://github.com/ovn-org/ovn/commit/ff7b737386feb1f7ed3d1e8d7218b0245990512d) rbac: Restrict IGMP_Group updates to relevant chassis.
- [ca8e0acc](https://github.com/ovn-org/ovn/commit/ca8e0accac6f4f5670ed011e67c7b103f549b06b) rbac: Only allow relevant chassis to update service monitors.
- [a69a13ca](https://github.com/ovn-org/ovn/commit/a69a13ca1814ab367db41db35935a6a83fd2054c) ovn-ctl: Use the current user for default file permissions.
- [3ae521f8](https://github.com/ovn-org/ovn/commit/3ae521f86379d45df830e5b5a09868341f820d02) ovn-trace: Make sure we don't exit when the port is not specified.
- [2713ec42](https://github.com/ovn-org/ovn/commit/2713ec4244393778e0d151e5b70aad08a15ee2bd) acl-log: Properly log the "pass" verdict.
- [cfea06cc](https://github.com/ovn-org/ovn/commit/cfea06cc8ac7e6b4526249ffa4d599f3bd9670da) automake: Make system tests dependent of ovn-macro.
- [ff978f6b](https://github.com/ovn-org/ovn/commit/ff978f6b8f88aeba6b8f96eed08a10e30b685ef9) ovn-controller.at: Fix flaky test "ofctrl wait before clearing flows".
- [bc73400a](https://github.com/ovn-org/ovn/commit/bc73400a0d5fcf480c2f43f72c180dd5d82b90d6) northd: fix infinite loop in ovn_allocate_tnlid()
- [10a24e55](https://github.com/ovn-org/ovn/commit/10a24e55f9ee7f46564f46cc3f4abd6fc4d7b2be) pinctrl: Fixed 100% cpu on ovs connection loss.
- [5dbe76a3](https://github.com/ovn-org/ovn/commit/5dbe76a326920bed6499d656278a6e6f27e69004) pinctrl: Fix missing MAC_Bindings.
- [9ff4e2b5](https://github.com/ovn-org/ovn/commit/9ff4e2b56d701772d90cf6b2f4a91b15a8158a4d) tests: Add macros to pause controller updates.
- [7d89c5e7](https://github.com/ovn-org/ovn/commit/7d89c5e7305935f933e8751aa272ea45c45a2200) ofctrl: Wait at S_WAIT_BEFORE_CLEAR only once.
- [d54f93e9](https://github.com/ovn-org/ovn/commit/d54f93e90073793e13e6faa45915033e4fccdf6c) northd: Fix population of ipv6_ra_prefixes from IPv6 PD.
- [ef62e81a](https://github.com/ovn-org/ovn/commit/ef62e81afab19705c6ba3a27d39905ab5ba85559) controller: Use multicast for IPv6 Prefix Delegation.
- [828d95e8](https://github.com/ovn-org/ovn/commit/828d95e8962f422cd13f926c22c9c3f3044b7e87) ovn-ic: Avoid igmp/mld traffic flooding.
- [1a396c49](https://github.com/ovn-org/ovn/commit/1a396c494453c32f818ba2fa6e6fbbdaee8ad6e5) IC: Tansit switch don't flood mcast traffic to router ports if matches igmp group.
- [4b3c6a2d](https://github.com/ovn-org/ovn/commit/4b3c6a2d4561d94791cd54160818301f012824eb) northd: Don't skip transit switch LSP when creating mcast groups.
- [12163f24](https://github.com/ovn-org/ovn/commit/12163f24b2a724d8ae41956498b87cbcf4534f0c) controller: Fix ofctrl memory usage underflow.
- [ec63d9ac](https://github.com/ovn-org/ovn/commit/ec63d9ac9ed7c9937cf2067f15a3d915f67948d4) docs: Remove ref. to "ovn-sbctl --no-wait".
- [e61d64a0](https://github.com/ovn-org/ovn/commit/e61d64a0b559379c527a5f9692c56751ad3a17d6) tests: Address netcat 7.94 changes.
- [1153bac3](https://github.com/ovn-org/ovn/commit/1153bac3421e07e35a375ce7959a012b9865eb4b) tests: Add helper for tcpdump.
- [8416cb0b](https://github.com/ovn-org/ovn/commit/8416cb0b9c196c89207b0e5e8a651a7da4e371f5) Fix broken link for LTS release.
- [c6f92d75](https://github.com/ovn-org/ovn/commit/c6f92d75b06b50930ebf3a9250700a75eabb2fad) ovn-controller: Fix busy loop when ofctrl is disconnected.
- [fa045473](https://github.com/ovn-org/ovn/commit/fa04547319caa903cfdaab8539492335a9628b15) utilities: Make database connection optional for ovn-detrace.
- [5f7396da](https://github.com/ovn-org/ovn/commit/5f7396da81fcfc51e33993965e19d759270261e2) ovn-controller: Stop dropping bind_vport requests immediately after handling.
- [b2947869](https://github.com/ovn-org/ovn/commit/b29478696598f991c02bde37bac082bfe9cc0f3f) tests: Fix flaky "lr multiple gw ports" test.
- [16ed4b18](https://github.com/ovn-org/ovn/commit/16ed4b182736cb2f5e7ecdde526dea2e97a9d2a4) pinctrl: Fix prefix delegation.
- [ed3a52d5](https://github.com/ovn-org/ovn/commit/ed3a52d5ab50c9090872d2065e75fb3ce2c2f298) controller: Release container lport when releasing parent port.
- [2b839636](https://github.com/ovn-org/ovn/commit/2b8396365dd25653abc7d7c2d722943711e964c1) github: Reduce ASLR entropy to be compatible with asan in llvm 14.
- [32036e7f](https://github.com/ovn-org/ovn/commit/32036e7f2e25e3cf7a6e0b745cc6025e834d4417) Prepare for 23.06.4.