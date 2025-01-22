+++
title = "Changelog v24.03.5"
[_build]
  list = 'never'
+++

### Changes from v24.03.4 to v24.03.5

- [f5a4704f](https://github.com/ovn-org/ovn/commit/f5a4704f9be07f7c29e45bb15e7e71126c6fea4a) Set release date for 24.03.5.
- [70618a65](https://github.com/ovn-org/ovn/commit/70618a65fd49f1d1d5498927c0bed63e296dafb7) Skip only OVN DNS responder packets from OUT_ACL.
- [2ee49f7a](https://github.com/ovn-org/ovn/commit/2ee49f7a27ed4b9a5785e97d6f9d5ea4dfa41fd8) Allow LR to send RAs through localnet port.
- [40004448](https://github.com/ovn-org/ovn/commit/400044489ab35aef4a02ec336ef894c518615ac9) controller: Update physical flows for peer port when the patch port is removed.
- [70f09a0e](https://github.com/ovn-org/ovn/commit/70f09a0e6d4a14b3aecb4b8f4bf46fcebb21f89a) northd: Trigger a full recompute if add-route option is toggled.
- [dd802680](https://github.com/ovn-org/ovn/commit/dd802680b2c15b2e1b541d45d177d2c643bb43ed) tests: Use IPv6 prefix reserved for documentation.
- [607009b8](https://github.com/ovn-org/ovn/commit/607009b880e5183ad44702026b74453b3511c8a4) tests: Explicitly store hex IPv6 PD prefix.
- [1138b822](https://github.com/ovn-org/ovn/commit/1138b822d438b859996c2eadaeb196dd43acc278) tests: Use /64s for IPv6 Prefix Delegation test.
- [368b1aac](https://github.com/ovn-org/ovn/commit/368b1aac561880d736b2ca1293c003788626b0fd) controller: binding: Set HTB root max-rate according to the link speed.
- [b842aa2c](https://github.com/ovn-org/ovn/commit/b842aa2cb057c9174e7a1d8105d1a4865f5504b9) tests: Add missing check for ovn-nbctl.
- [657d6df0](https://github.com/ovn-org/ovn/commit/657d6df058da2f66950b0bf2cfe1a0ad2f4c32d1) tests: Add check_uuid in tests.
- [e3dd3ee4](https://github.com/ovn-org/ovn/commit/e3dd3ee4dc1161981dfeb333a3a9d12ec1fe75cf) test: ovn-northd: Use check for ovn-nbctl wherever possible.
- [5c67017b](https://github.com/ovn-org/ovn/commit/5c67017ba448ee22a55fbf2ad8d854d9ddc8ffa3) test: Use check for ovn-sbctl wherever possible.
- [b201c431](https://github.com/ovn-org/ovn/commit/b201c431d6304663803c7eec80c081f5da8b2d86) test: system-ovn: Use check for ovn-nbctl wherever possible.
- [8374312f](https://github.com/ovn-org/ovn/commit/8374312f1ee4dd59e92f7ab157c730791eb8148f) test: ovn: Use check for ovn-nbctl wherever possible.
- [e7f754c4](https://github.com/ovn-org/ovn/commit/e7f754c4b7be82562528b3ac828a1456e3f25580) northd: Don't SNAT reply packets on LBs with lb_force_snat_ip set.
- [f35818a5](https://github.com/ovn-org/ovn/commit/f35818a5e71647a19af7f9a94e40ad5b5afe32aa) system-tests: Add check for LB related in reply direction.
- [8e831cc7](https://github.com/ovn-org/ovn/commit/8e831cc7de8aa04bcb982ed5164caa9d58119d93) tests: Fix flaky "ovn-controller incremental processing".
- [5d0ebb45](https://github.com/ovn-org/ovn/commit/5d0ebb455711edd59def6a5eb820dfa2080067a9) tests: Fix flaky "ovs-appctl -t ovsdb-server ...".
- [658a4465](https://github.com/ovn-org/ovn/commit/658a44655ae750e82355aee5084fc7109fbe4242) tests: Fix flaky "ovn-sbctl - ovn-sbctl - count-flows - daemon".
- [1d814289](https://github.com/ovn-org/ovn/commit/1d814289c99eb0da71bdde90ffa502f2fbf38373) tests: Fix flaky "OVN FDB (MAC learning)".
- [f9903e42](https://github.com/ovn-org/ovn/commit/f9903e427455c3989a04f8e38e6b0fcff6ed2b86) tests: Fix flaky "ovn-controller-vtep - chassis".
- [1f649716](https://github.com/ovn-org/ovn/commit/1f649716e7adcfe8f2d27cc32fd14b745beb2260) tests: Fix flaky "controller event".
- [1d3946a1](https://github.com/ovn-org/ovn/commit/1d3946a111233c96565276a3639ce7ba7ed2a813) tests: Fix flaky "send gratuitous arp with nat-addresses ...".
- [49676fe7](https://github.com/ovn-org/ovn/commit/49676fe75f97cf8f1a99aaaf5fbc2a19e8f63cf7) tests: Fix flaky "ofctrl wait before clearing flows".
- [04c852a1](https://github.com/ovn-org/ovn/commit/04c852a1d7fe3d2d34c1fb7dbb1ff26ea2e3b7b8) tests: Implement send_garp using scapy.
- [47c92cec](https://github.com/ovn-org/ovn/commit/47c92ceccdf1db3c90439a634194040ca048d8d5) docs: Fix route lookup behavior description.
- [ecffd338](https://github.com/ovn-org/ovn/commit/ecffd3387f0aae87fe481881068c38f3889ac574) controller: Reduce the time it takes to remove multiple ports.
- [68241f15](https://github.com/ovn-org/ovn/commit/68241f15570ac8bc8b7252b037e3bde8726cbeab) controller: Properly handle localnet flows in I+P.
- [21e14f6a](https://github.com/ovn-org/ovn/commit/21e14f6af4f5ec7335141f1a7ad59aa4e911a066) Allow LR to send RAs with only link local Ipv6.
- [ce194536](https://github.com/ovn-org/ovn/commit/ce1945367ba1ebd3634abb44d4d23a55d63ec7f8) tests: Fix typos found using check_uuid.
- [4dcb4b0c](https://github.com/ovn-org/ovn/commit/4dcb4b0c3be750a75bd8fc4235865c1d73495246) northd: Fix issues in RBAC tables recovery.
- [17b17dfd](https://github.com/ovn-org/ovn/commit/17b17dfda01b42913d4c671bbda692fdbf881995) logical-fields: Reuse registers for ct_*_dst() actions.
- [29113e8d](https://github.com/ovn-org/ovn/commit/29113e8da452181e8b364c08e98a5c8de5fb88bc) lex: Indicate that the template wasn't found during parsing.
- [b751a1a0](https://github.com/ovn-org/ovn/commit/b751a1a050a1d8c2ca36699ce81b8e9126c2034a) controller: Prevent crash when db is empty.
- [78e52c2f](https://github.com/ovn-org/ovn/commit/78e52c2f2358978cd28899a02cc7e5edad0cd1a1) test: system-ovn: Fix typos in system-test
- [44fd4383](https://github.com/ovn-org/ovn/commit/44fd438348c10186e2be3f09872dfd4778ab9200) test: ovn-northd: Fix typos in unit-test
- [8477b177](https://github.com/ovn-org/ovn/commit/8477b177b570bd6b5edfbdabadc3695ea680172c) test: ovn: Fix typos in unit-test
- [81ef8570](https://github.com/ovn-org/ovn/commit/81ef85707ed7959da629b6481edb0e943693abaa) northd: Don't generate IPv6 prefix delegation flows if not configured.
- [120ba7d8](https://github.com/ovn-org/ovn/commit/120ba7d8754d697bf129df06e2dbfc4598e3a1fd) northd: Add missing multicast match to DHCPv6 options flows.
- [1ab5555c](https://github.com/ovn-org/ovn/commit/1ab5555c351aab44a5e0e6d528ef19dba848138f) northd: Populate additional-chassis to HA group.
- [3a3b28d9](https://github.com/ovn-org/ovn/commit/3a3b28d94b141d4f4900331999323e7b2581f635) Fix load balanced hairpin traffic for fragmented packets.
- [570b968c](https://github.com/ovn-org/ovn/commit/570b968c25d76a767416d27b691b8262add424c4) tests: Wait for controller exit before restart.
- [c5d851bb](https://github.com/ovn-org/ovn/commit/c5d851bb53dc39d6bfcac7df806c64e58c0cd77b) Revert "controller: Properly handle localnet flows in I+P.".
- [ed9b0cff](https://github.com/ovn-org/ovn/commit/ed9b0cfff9439fce686ab0393323e588096e52ba) pinctrl: Skip non-local mac bindings in run_buffered_binding().
- [0ab05e52](https://github.com/ovn-org/ovn/commit/0ab05e52649de1dfe2412d3305690081199df8ac) pinctrl: Skip deleted mac bindings in run_buffered_binding().
- [75737597](https://github.com/ovn-org/ovn/commit/75737597e0e1281250a0f04bb8eb3a54fcf05292) mac-cache: Properly handle deletion of SB mac_bindings.
- [6a379bd4](https://github.com/ovn-org/ovn/commit/6a379bd46b6d23532c3335a7c6cd0676db85c0ba) controller: Fix "use after free" issue in statctrl_run().
- [ca88ccb9](https://github.com/ovn-org/ovn/commit/ca88ccb91aa11fa8e88e41d83d9423ee4e584506) Prepare for 24.03.5.