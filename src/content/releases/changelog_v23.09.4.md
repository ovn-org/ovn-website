+++
title = "Changelog v23.09.4"
[_build]
  list = 'never'
+++

### Changes from v23.09.3 to v23.09.4

- [6b20443](https://github.com/ovn-org/ovn/commit/6b204436d028d49765929671b20b7f4bc0248a52) Set release date for 23.09.4.
- [5233cea](https://github.com/ovn-org/ovn/commit/5233cea52d1878786bc55ff5eccc309ea2667964) controller: Fix an issue wrt cleanup of stale patch port.
- [b2d306b](https://github.com/ovn-org/ovn/commit/b2d306be940456ffb15e014d49ae66516b16dcb1) utilities: Add ovn-debug binary tool.
- [3a817c8](https://github.com/ovn-org/ovn/commit/3a817c8684c30de0de35742753adb74c3a9b2f0f) controller: Track individual address set constants.
- [465d2db](https://github.com/ovn-org/ovn/commit/465d2db2f3e518907879fe400e6d429aa095ad74) ci: Fix OPTS not being passed to OSX builds.
- [e5c3331](https://github.com/ovn-org/ovn/commit/e5c3331cb8d821eddde48111ad9b387c55c1f87a) northd, controller: Use paused controller action for packet buffering.
- [fc0d7b7](https://github.com/ovn-org/ovn/commit/fc0d7b7aea6f8c13a9a119abd78696f8a3f5dcf0) ovs: Bump the submodule to the tip of branch-3.2.
- [441a4c2](https://github.com/ovn-org/ovn/commit/441a4c2aa3aab052c4a03b57d659045a285d41b6) northd: Do not incrementally proccess changes for disabled LR.
- [33f6e25](https://github.com/ovn-org/ovn/commit/33f6e25420197f8b779606cd464105e054a73443) ovn-nbctl: Document "--portrange" in the manpage.
- [bd204aa](https://github.com/ovn-org/ovn/commit/bd204aa3575e9e201da04f57e85c849999a4ddc5) rbac: Only allow relevant chassis to update BFD.
- [692c0ae](https://github.com/ovn-org/ovn/commit/692c0ae67af485480a7f6d9e68758c694dd08dcc) rbac: Restrict IGMP_Group updates to relevant chassis.
- [c633e63](https://github.com/ovn-org/ovn/commit/c633e6347b216a43757517da576525857b82f875) rbac: Only allow relevant chassis to update service monitors.
- [77f3ce3](https://github.com/ovn-org/ovn/commit/77f3ce3051f91567d2b533eeb26b822f0c0f146c) ovn-ctl: Use the current user for default file permissions.
- [a2b2776](https://github.com/ovn-org/ovn/commit/a2b2776852a7d602db62222d83a194427df500c9) ovn-trace: Make sure we don't exit when the port is not specified.
- [d2c4908](https://github.com/ovn-org/ovn/commit/d2c49087c83999db6b7804e13c5e042a0d4de528) acl-log: Properly log the "pass" verdict.
- [b73e667](https://github.com/ovn-org/ovn/commit/b73e6678ffcff29932535053eef825ea5158c570) automake: Make system tests dependent of ovn-macro.
- [0b5a068](https://github.com/ovn-org/ovn/commit/0b5a068b67e431c05ea3e12d583289d108fb6901) ovn-controller.at: Fix flaky test "ofctrl wait before clearing flows".
- [cfda5f6](https://github.com/ovn-org/ovn/commit/cfda5f6421e7c6418725fe9e2f7033adbfc33957) northd: fix infinite loop in ovn_allocate_tnlid()
- [df3e643](https://github.com/ovn-org/ovn/commit/df3e643a78a78ecdc442af17365f1270ee43db8d) pinctrl: Fixed 100% cpu on ovs connection loss.
- [1d803d7](https://github.com/ovn-org/ovn/commit/1d803d7a9f264dce8224bc08bc98e260fe4fbc1b) pinctrl: Fix missing MAC_Bindings.
- [83a271b](https://github.com/ovn-org/ovn/commit/83a271b19806ad4e544f3ba344c4513a972dc5ca) tests: Add macros to pause controller updates.
- [c8e2ed3](https://github.com/ovn-org/ovn/commit/c8e2ed393ca956ed5723a912616da7dcc6c7dff9) ofctrl: Wait at S_WAIT_BEFORE_CLEAR only once.
- [386af5c](https://github.com/ovn-org/ovn/commit/386af5cc1401703be5681ad693b2e64a5808404c) northd: Fix population of ipv6_ra_prefixes from IPv6 PD.
- [2dbf62d](https://github.com/ovn-org/ovn/commit/2dbf62d13d524eb622baa0464426ec1e8d65f647) controller: Use multicast for IPv6 Prefix Delegation.
- [8091ef7](https://github.com/ovn-org/ovn/commit/8091ef796ee6b708df4397489b12257636342382) ovn-ic: Avoid igmp/mld traffic flooding.
- [545cf9a](https://github.com/ovn-org/ovn/commit/545cf9a8bdfe65fc6df02ef70e8a9c5d03a47fde) IC: Tansit switch don't flood mcast traffic to router ports if matches igmp group.
- [03e4603](https://github.com/ovn-org/ovn/commit/03e4603b7d6ad9f2ed686857b1aaeae50fb97af1) northd: Don't skip transit switch LSP when creating mcast groups.
- [3bfb1c9](https://github.com/ovn-org/ovn/commit/3bfb1c9a2a75fe15383c83595b0e4a615d52e2e7) controller: Fix ofctrl memory usage underflow.
- [39f711a](https://github.com/ovn-org/ovn/commit/39f711a2f0fc14ffb50015d1151d91aebe361d3c) docs: Remove ref. to "ovn-sbctl --no-wait".
- [ef214c6](https://github.com/ovn-org/ovn/commit/ef214c6e572641925561b4fff2a824cdfda9736f) tests: Address netcat 7.94 changes.
- [2d41ae9](https://github.com/ovn-org/ovn/commit/2d41ae94c0e1d2dc5b04d0301d53b5f92d67eaf0) tests: Add helper for tcpdump.
- [4f8cc43](https://github.com/ovn-org/ovn/commit/4f8cc4337e26ac42c2636d0a82542aad0ac471a0) Fix broken link for LTS release.
- [40b670e](https://github.com/ovn-org/ovn/commit/40b670e6ee94f54b249c051f301e46354e62dab6) ovn-controller: Fix busy loop when ofctrl is disconnected.
- [5691e51](https://github.com/ovn-org/ovn/commit/5691e51def9d0a6c3a4f821321c03b8e91207fed) utilities: Make database connection optional for ovn-detrace.
- [d9a67bd](https://github.com/ovn-org/ovn/commit/d9a67bd9b2164b854b58927f82a015e564e6e44e) ovn-controller: Stop dropping bind_vport requests immediately after handling.
- [4005415](https://github.com/ovn-org/ovn/commit/4005415408dd534d849473242b3a551877ee19f4) tests: Fix flaky "lr multiple gw ports" test.
- [e49e73c](https://github.com/ovn-org/ovn/commit/e49e73ca7e80150e46f54466d2c9617739bd70f7) pinctrl: Fix prefix delegation.
- [277883a](https://github.com/ovn-org/ovn/commit/277883acfc7535d8e5ebfc544e48c1498aab6faf) controller: Release container lport when releasing parent port.
- [2caee3e](https://github.com/ovn-org/ovn/commit/2caee3ee0b84a8db03982fab8ce8ceac7ec1068c) ovn-ic: Destroy the created index row for ts.
- [835b438](https://github.com/ovn-org/ovn/commit/835b43811dfcf469da3123911240cc953b52bac3) github: Reduce ASLR entropy to be compatible with asan in llvm 14.
- [5ce1740](https://github.com/ovn-org/ovn/commit/5ce1740aaa02ebeed561ffb6298b71035b5c908a) Prepare for 23.09.4.