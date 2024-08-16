+++
title = "Changelog v24.03.2"
[_build]
  list = 'never'
+++

### Changes from v24.03.1 to v24.03.2

- [41836afa](https://github.com/ovn-org/ovn/commit/41836afafd99d579bb277f638a31bffd5cf3efa3) Set release date for 24.03.2.
- [8cde6c5a](https://github.com/ovn-org/ovn/commit/8cde6c5a8c308a6b293c9510b845de81a5afb932) controller: Fix an issue wrt cleanup of stale patch port.
- [765f80c6](https://github.com/ovn-org/ovn/commit/765f80c6470bf9e92f58ed57691cae303a2e6cd5) utilities: Add ovn-debug binary tool.
- [40a26831](https://github.com/ovn-org/ovn/commit/40a268313c35751d65c35e6d13154a99a3c6069f) controller: Track individual address set constants.
- [20ab6c83](https://github.com/ovn-org/ovn/commit/20ab6c83f57fe14154f5b117138c512fc6b49388) northd, controller: Handle tunnel_key change consistently.
- [70d3a10e](https://github.com/ovn-org/ovn/commit/70d3a10e18bf9327ca0c1995624be49fdf90392a) tests: Add macro for checking flows after recompute.
- [0cfe12a7](https://github.com/ovn-org/ovn/commit/0cfe12a7901d6f5189675d5fe76a021a798124a1) ci: Keep the container version pinned.
- [e4c380fa](https://github.com/ovn-org/ovn/commit/e4c380fa8d3389d4b066611585b24e0d561a7a0a) ci: Fix OPTS not being passed to OSX builds.
- [af62f9f4](https://github.com/ovn-org/ovn/commit/af62f9f4e2bc604d555e1a7773d40856a2ac093f) Add dh-python to debian/control.
- [cfeeaa6e](https://github.com/ovn-org/ovn/commit/cfeeaa6e2fb3e0bed9d608259025473808d286c2) tests: Fix netcat 7.94 issues.
- [1e89d06e](https://github.com/ovn-org/ovn/commit/1e89d06e62caff88cab9c31f1b1b2ec8dfe64880) northd, controller: Use paused controller action for packet buffering.
- [ac0af22f](https://github.com/ovn-org/ovn/commit/ac0af22fb4c5fe2cea4aee38580fe39aec26e245) northd: Do not incrementally proccess changes for disabled LR.
- [ccaf22f1](https://github.com/ovn-org/ovn/commit/ccaf22f1356a6a82514e893b204366621c04aad3) northd: Fix direct access to SNAT network.
- [92f7a974](https://github.com/ovn-org/ovn/commit/92f7a974cbe79fe9de6f4d92440eebe41e4ec015) actions: New action ct_commit_to_zone.
- [76321c07](https://github.com/ovn-org/ovn/commit/76321c078749cdcaf2df52e44b37864a15c28b76) ovn-nbctl: Document "--portrange" in the manpage.
- [d45c0631](https://github.com/ovn-org/ovn/commit/d45c06312d859fb76297a44533ce80082d0067a9) utilities: Add missing bfd option in ovn-nbctl manpage.
- [6d71cbfd](https://github.com/ovn-org/ovn/commit/6d71cbfd1811b97a5aa7c5b9c9f957ef8579234f) ovs: Bump the submodule to the tip of branch-3.3.
- [7346953e](https://github.com/ovn-org/ovn/commit/7346953e2fe39a4e8a7871da4f2634050feb1659) ovn-ctl: Use the current user for default file permissions.
- [419f8a83](https://github.com/ovn-org/ovn/commit/419f8a836c42db2a35a550cf4a4e975e3a3eb2af) ovn-trace: Make sure we don't exit when the port is not specified.
- [a6095e1c](https://github.com/ovn-org/ovn/commit/a6095e1cb237016191519478fbef9f775a67bc89) northd: Fix BFD for policy routing.
- [6eff687d](https://github.com/ovn-org/ovn/commit/6eff687d5f42dd4cb4558b071aaa00d5a55667f6) acl-log: Properly log the "pass" verdict.
- [90c577ae](https://github.com/ovn-org/ovn/commit/90c577ae544e0d16593d5a89c058276ff25d43e3) automake: Make system tests dependent of ovn-macro.
- [2ab187e9](https://github.com/ovn-org/ovn/commit/2ab187e9bb6c9be6174529df9617534aef6a3a94) ovn-controller.at: Fix flaky test "ofctrl wait before clearing flows".
- [69e90f66](https://github.com/ovn-org/ovn/commit/69e90f664a1130a5415904d41db6dba713eea8c2) northd: fix infinite loop in ovn_allocate_tnlid()
- [72390c4f](https://github.com/ovn-org/ovn/commit/72390c4fea72cfbae5eb9409abb8a6dd7d5f3e69) pinctrl: Fixed 100% cpu on ovs connection loss.
- [c7674665](https://github.com/ovn-org/ovn/commit/c76746653f8423d514d3374423a3e15b0ede86bd) pinctrl: Fix missing MAC_Bindings.
- [1187031d](https://github.com/ovn-org/ovn/commit/1187031d5ebf3fb0a79b16f48798d88829175702) tests: Add macros to pause controller updates.
- [6b1618a9](https://github.com/ovn-org/ovn/commit/6b1618a96f178b7b7d6a0c1903291f4bc4cc7f1d) ofctrl: Wait at S_WAIT_BEFORE_CLEAR only once.
- [bad2e304](https://github.com/ovn-org/ovn/commit/bad2e3042e9cdac38db058ab0ce1478f104fef03) northd: Fix population of ipv6_ra_prefixes from IPv6 PD.
- [5ff0e2ae](https://github.com/ovn-org/ovn/commit/5ff0e2aee3553e52766eb1c34ccc203ad6022fde) controller: Use multicast for IPv6 Prefix Delegation.
- [29af310c](https://github.com/ovn-org/ovn/commit/29af310ce16fcaf0a9ce18aa79bf44d5cf0cf1e4) ovn-ic: Avoid igmp/mld traffic flooding.
- [d1a72533](https://github.com/ovn-org/ovn/commit/d1a7253333ace9db7b3cef68b74a7f190fcaca8b) tests: Use sync command in ovn-ic tests.
- [ef2e7118](https://github.com/ovn-org/ovn/commit/ef2e711819d517de7abf91d4c8edef9818a92346) tests: Move ovn interconnection tests to ovn-ic.at.
- [31c7d227](https://github.com/ovn-org/ovn/commit/31c7d227dc2bef55f1f1d6f07abd1b21831c0ab2) IC: Tansit switch don't flood mcast traffic to router ports if matches igmp group.
- [6af50a99](https://github.com/ovn-org/ovn/commit/6af50a99c6e4836cc29471cbcbe0a938c3aa1879) northd: Don't skip transit switch LSP when creating mcast groups.
- [1434d1bc](https://github.com/ovn-org/ovn/commit/1434d1bc55ed43994dba769b1070317476b9f1b0) northd: Fix NAT configuration with --add-route option for gw-router.
- [3e35d0da](https://github.com/ovn-org/ovn/commit/3e35d0daeac162437a5858d3ea6e3d508462184a) controller: Fix ofctrl memory usage underflow.
- [5b388024](https://github.com/ovn-org/ovn/commit/5b3880242ba55f81f93ebccd0a91978e7d65ba06) docs: Remove ref. to "ovn-sbctl --no-wait".
- [5f7765b2](https://github.com/ovn-org/ovn/commit/5f7765b238be0aa323a3ded21f5bbe770cc75daf) Fix broken link for LTS release.
- [b213cb64](https://github.com/ovn-org/ovn/commit/b213cb641a050f5294ba592196823dd7fe529ad2) ovn-controller: Fix busy loop when ofctrl is disconnected.
- [653e010f](https://github.com/ovn-org/ovn/commit/653e010f1e2c7032e612c68ba34d968569c0e0c5) tests: Address netcat 7.94 changes.
- [f739c28e](https://github.com/ovn-org/ovn/commit/f739c28e822332e28e46f083b9a85c4ccbf51691) tests: Add helper for tcpdump.
- [9644436a](https://github.com/ovn-org/ovn/commit/9644436abc183a9ccd8434fdef4b5823b8855f9f) tests: Ignore transaction errors in MAC Binding.
- [f60d06f3](https://github.com/ovn-org/ovn/commit/f60d06f3ae1fd6b1527e0e9f61bcc85c8383cfbb) utilities: Make database connection optional for ovn-detrace.
- [0e85aa32](https://github.com/ovn-org/ovn/commit/0e85aa326847b8a4075753bab8ede7f991cb912b) ovn-controller: Stop dropping bind_vport requests immediately after handling.
- [d72b3f90](https://github.com/ovn-org/ovn/commit/d72b3f90e3991cca1211146401c848d35f2b6012) tests: Fix flaky "lr multiple gw ports" test.
- [735a81fe](https://github.com/ovn-org/ovn/commit/735a81fec9b8f1fd769b5e3f4018702b8c4f03ca) pinctrl: Fix prefix delegation.
- [d5d4c3bf](https://github.com/ovn-org/ovn/commit/d5d4c3bf25f8d85523b22c3b3746f53ce1f6c767) controller: Release container lport when releasing parent port.
- [06d3a8fe](https://github.com/ovn-org/ovn/commit/06d3a8fe48969aa7be4f8672ff77a386a1defab6) github: Reduce ASLR entropy to be compatible with asan in llvm 14.
- [ffd8bb1a](https://github.com/ovn-org/ovn/commit/ffd8bb1a1bd90cce2be4eed37503332c91c5d0e3) Prepare for 24.03.2.