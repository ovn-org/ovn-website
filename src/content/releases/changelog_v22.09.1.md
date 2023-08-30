+++
title = "Changelog v22.09.1"
[_build]
  list = 'never'
+++

### Changes from v22.09.0 to v22.09.1

- [eaee3ed4](https://github.com/ovn-org/ovn/commit/eaee3ed4391ba3477fe98f36795e01d81f008323) Set release date for 22.09.1.
- [c38fb64f](https://github.com/ovn-org/ovn/commit/c38fb64f4f13cb4216b4952f650306682dd9e2d6) ic: minor code improvements
- [d26dc8ec](https://github.com/ovn-org/ovn/commit/d26dc8ec5c3c47032798cea30894ddb14a8b879b) ic: prevent advertising/learning multiple same routes
- [c84d8852](https://github.com/ovn-org/ovn/commit/c84d8852cb5ae381f6f71485df14f7c90522771f) ic: lookup southbound port_binding only if needed
- [bafe7795](https://github.com/ovn-org/ovn/commit/bafe7795328f959778746c09bfde7fa590b95f08) ic: remove orphan ovn interconnection routes
- [525829c4](https://github.com/ovn-org/ovn/commit/525829c47d09a114de8536d23784c458977d8321) ovn-controller: Only set monitor conditions on available tables.
- [cd52e0a3](https://github.com/ovn-org/ovn/commit/cd52e0a31ac6932c67beaa723f27ecb9a050f71e) ovn-trace: Support connecting to SB raft followers.
- [034fe0d8](https://github.com/ovn-org/ovn/commit/034fe0d8ae4af75f625c6d3048612de7befb154f) CI: Remove .cirrus.yml
- [330c1473](https://github.com/ovn-org/ovn/commit/330c1473f7e008255435d7469fbbe60c892bffe6) controller: Check if MAC binding table has timestamp column
- [a85e2446](https://github.com/ovn-org/ovn/commit/a85e24467ea74aae5d777e38e607b6dcf8022761) northd: Add missing RBAC rules for BFD table.
- [0043857e](https://github.com/ovn-org/ovn/commit/0043857e86d7a7bad4ee3fc1102216d7b5df7cae) ovn-nbctl: Fix removal of BFD entry on route deletion
- [db61b2e4](https://github.com/ovn-org/ovn/commit/db61b2e4f166092e5bc93f4cba7696a72037a069) controller: Fixed ovs/ovn(features) connection lost when running more than 120 seconds
- [d62dde64](https://github.com/ovn-org/ovn/commit/d62dde642879ffb7ff1eb8f4077b6224f977c6d7) ovs: Bump submodule to include latest fixes.
- [90c165fa](https://github.com/ovn-org/ovn/commit/90c165fa5a6ecdd9bac606cf259ae88228b96208) ovn-controller: Fixed missing flows after interface deletion
- [4da7a269](https://github.com/ovn-org/ovn/commit/4da7a269c9eb055b2cfa27d67593a77167b8c9a6) ovn-controller: Fix releasing wrong vif
- [ef15d5c2](https://github.com/ovn-org/ovn/commit/ef15d5c22fa2255db69be2d6da822cefb099327c) tests: Fix flaky test "multi-vtep SB Chassis encap updates"
- [ae96d5d7](https://github.com/ovn-org/ovn/commit/ae96d5d753ccbee9b239178f56460e05169ac9f7) controller: Fix QoS for ports with undetected or too low link speed.
- [0fc04166](https://github.com/ovn-org/ovn/commit/0fc041667031da20cd03c0b76de8de3dbe502d50) ovn-controller: Fix some issues with CT zone assignment.
- [bc609bf1](https://github.com/ovn-org/ovn/commit/bc609bf148be3a38a0b8f38f049f30eb7e9b55f8) ci: Update jobs to use numbers instead of test flags
- [c18415d5](https://github.com/ovn-org/ovn/commit/c18415d5ae7273c633190df4ac9e872a0a0f9709) ovs: Bump submodule to tip of branch-3.0 and add related test
- [f2042a2e](https://github.com/ovn-org/ovn/commit/f2042a2e6aeb1a7fe266316337545331f5186dd0) controller: fix ipv6 prefix delegation in gw router mode
- [29e4d439](https://github.com/ovn-org/ovn/commit/29e4d43966fbf34d9707e31880c455f22a643bb3) spec: require python3-openvswitch for ovn-detrace
- [51044dbf](https://github.com/ovn-org/ovn/commit/51044dbfdba234a3f50d8c9c952335e41b72a39b) northd: Use separate SNAT for already-DNATted traffic.
- [86e99bf9](https://github.com/ovn-org/ovn/commit/86e99bf95a2191ebdcd5d03335ff8add2a636f55) controller: Restore MAC and vlan for DVR scenario
- [40dd85eb](https://github.com/ovn-org/ovn/commit/40dd85eb8d2d2d88f9000b6be6fb263b4bd1a27f) northd: Fix multicast table full
- [76a01e53](https://github.com/ovn-org/ovn/commit/76a01e53a9fcc3184211cca10787d462cb86a352) controller: Fix first ping from lsp to external through snat failing
- [854c2b1a](https://github.com/ovn-org/ovn/commit/854c2b1a4ba9ef35e03348d1bd4fc8265f3f74a3) Prepare for 22.09.1.