+++
title = "Changelog v24.09.2"
[_build]
  list = 'never'
+++

### Changes from v24.09.1 to v24.09.2

- [df4f80a6](https://github.com/ovn-org/ovn/commit/df4f80a60d4cd712870aa73d32d5677448c11c78) Set release date for 24.09.2.
- [249c52ad](https://github.com/ovn-org/ovn/commit/249c52ad011cacb4c182dc64e88977ac7c61f668) Skip only OVN DNS responder packets from OUT_ACL.
- [bf1a2228](https://github.com/ovn-org/ovn/commit/bf1a2228e3486edcec53641eb6fb01e041b84244) Allow LR to send RAs through localnet port.
- [b48f7ea4](https://github.com/ovn-org/ovn/commit/b48f7ea49883385ab8e4420ce8005ea0d9c3f866) controller: Update physical flows for peer port when the patch port is removed.
- [ce5d98c8](https://github.com/ovn-org/ovn/commit/ce5d98c8afdd8b35118c4ee8f6e2240e0b76a577) northd: Trigger a full recompute if add-route option is toggled.
- [e7d8d5de](https://github.com/ovn-org/ovn/commit/e7d8d5de2bc72dee77fc2b8e58fbaf75fd351a0e) tests: Use IPv6 prefix reserved for documentation.
- [e37046c1](https://github.com/ovn-org/ovn/commit/e37046c13d7933c64d48525e172f422cc33300ea) tests: Explicitly store hex IPv6 PD prefix.
- [31e286d7](https://github.com/ovn-org/ovn/commit/31e286d702d1fc8eda2a2aaf0c99efbe99c9a983) tests: Use /64s for IPv6 Prefix Delegation test.
- [32a0307c](https://github.com/ovn-org/ovn/commit/32a0307c45e66682afd34853dd1beb4d7a925ba3) controller: binding: Set HTB root max-rate according to the link speed.
- [e3b6aecf](https://github.com/ovn-org/ovn/commit/e3b6aecf576ee580749c54d5d3887df784d4b5bb) tests: Add missing check for ovn-nbctl.
- [2d632694](https://github.com/ovn-org/ovn/commit/2d632694074923207539fd0def25fb365987bdab) tests: Add check_uuid in tests.
- [073c5b9d](https://github.com/ovn-org/ovn/commit/073c5b9d108bff0e36209bfc044bbca49d0edc2a) test: ovn-northd: Use check for ovn-nbctl wherever possible.
- [e9464efe](https://github.com/ovn-org/ovn/commit/e9464efebb81f25c20489f3c2d254b7070b0daa5) test: Use check for ovn-sbctl wherever possible.
- [ccffaece](https://github.com/ovn-org/ovn/commit/ccffaecea0b3a6a2be3ec187f444c30f2c59b5b7) test: system-ovn: Use check for ovn-nbctl wherever possible.
- [8c4ad146](https://github.com/ovn-org/ovn/commit/8c4ad146c941e13d57568b3e127dd8db1b6df210) test: ovn: Use check for ovn-nbctl wherever possible.
- [b6e3a5d0](https://github.com/ovn-org/ovn/commit/b6e3a5d05580486c9da596e637e0223d48c19a26) northd: Don't SNAT reply packets on LBs with lb_force_snat_ip set.
- [6af14b4c](https://github.com/ovn-org/ovn/commit/6af14b4ce62aec4dc43965cdbfa758627756d769) system-tests: Add check for LB related in reply direction.
- [95d42245](https://github.com/ovn-org/ovn/commit/95d42245538d906e095a243205151f8841cb0835) tests: Fix flaky "ovn-controller incremental processing".
- [3fbf688d](https://github.com/ovn-org/ovn/commit/3fbf688d8efc081255b8fd943454ea0cc19d0658) tests: Fix flaky "ovs-appctl -t ovsdb-server ...".
- [6245a8e2](https://github.com/ovn-org/ovn/commit/6245a8e27d9a7ab149ed44795bd678813a4a9045) tests: Fix flaky "ovn-controller - I-P different port types".
- [a4e2fdbd](https://github.com/ovn-org/ovn/commit/a4e2fdbd2ff1e9914d9745ec44d7ff2783cffe8d) tests: Fix flaky "ovn-sbctl - ovn-sbctl - count-flows - daemon".
- [8c000ef3](https://github.com/ovn-org/ovn/commit/8c000ef351370d46db7bb47c1fa30bd6823cc75b) tests: Fix flaky "OVN FDB (MAC learning)".
- [7d802ab5](https://github.com/ovn-org/ovn/commit/7d802ab57730c9e87096becad105da9f2e18ac2e) tests: Fix flaky "ovn-controller-vtep - chassis".
- [8ba2d42d](https://github.com/ovn-org/ovn/commit/8ba2d42d1304ebb6e7dc7062163df0e9c2ca274e) tests: Fix flaky ovn-controller - CT zone min/max boundaries.
- [92442227](https://github.com/ovn-org/ovn/commit/924422271d48e76d63e1041f561ebbe6ece7ac68) tests: Fix flaky "controller event".
- [3f5b0e5f](https://github.com/ovn-org/ovn/commit/3f5b0e5fb16342d14d617e20d59b58834d420b1b) tests: Fix flaky "send gratuitous arp with nat-addresses ...".
- [5bef1be8](https://github.com/ovn-org/ovn/commit/5bef1be8e0fd0f892370b5478c9c7e8a0551fb32) tests: Fix flaky "DHCP RELAY".
- [13cb3b99](https://github.com/ovn-org/ovn/commit/13cb3b99670e74cb969bf57416e958aef1889308) tests: Fix flaky "ofctrl wait before clearing flows".
- [d53d3e6a](https://github.com/ovn-org/ovn/commit/d53d3e6a5f43510b0e3d4193bb285cf8bede70f4) tests: Implement send_garp using scapy.
- [5d3a4e00](https://github.com/ovn-org/ovn/commit/5d3a4e00178189d827156be32ebb39fc80dc027b) ovn-controller dns-cache: Improve dns caching using cmaps.
- [299b503e](https://github.com/ovn-org/ovn/commit/299b503e30e4243a6b39b31e42a54fcee4b66fe3) pinctrl: Use ovs_mutex_trylock() in the pinctrl thread.
- [cd08caf5](https://github.com/ovn-org/ovn/commit/cd08caf5b83aa26cbf407c1672cfb189eb39353c) northd: Use the same UUID for SB representation of DNS.
- [1d6465ba](https://github.com/ovn-org/ovn/commit/1d6465ba66ff793c4c9c3ddee2f02e8012475800) ovn-controller: Add a separate dns cache module and I-P for SB DNS.
- [bc32ead4](https://github.com/ovn-org/ovn/commit/bc32ead4b65c23cfe3b56bceb6feb2ae4390bd66) docs: Fix route lookup behavior description.
- [48429296](https://github.com/ovn-org/ovn/commit/48429296e8dcc64fb5835d3a604e0de3edb2cee4) controller: Reduce the time it takes to remove multiple ports.
- [c0d27b82](https://github.com/ovn-org/ovn/commit/c0d27b82eb8f55dd0e03e67bc9e8cd5aa609311b) controller: Properly handle localnet flows in I+P.
- [d99046b8](https://github.com/ovn-org/ovn/commit/d99046b8a413bca109921d722125f727513bce6a) Allow LR to send RAs with only link local Ipv6.
- [fd9d5f2e](https://github.com/ovn-org/ovn/commit/fd9d5f2e81aa7ed4127b0151f85acacca8c183f3) tests: Fix typos found using check_uuid.
- [177ce930](https://github.com/ovn-org/ovn/commit/177ce930c3012c53f171c2ff88365baa8f8233f0) northd: Track max ACL tiers more accurately.
- [1fd216f1](https://github.com/ovn-org/ovn/commit/1fd216f1ae6c3916f4032048686162e03ee92f1c) northd: Fix issues in RBAC tables recovery.
- [031032b4](https://github.com/ovn-org/ovn/commit/031032b40256396b2b2c6d20d49eea4e45d466dc) logical-fields: Reuse registers for ct_*_dst() actions.
- [0a767e8d](https://github.com/ovn-org/ovn/commit/0a767e8d889e6b92a89621e4b40c5b05e44d1bd2) lex: Indicate that the template wasn't found during parsing.
- [cbf97bd8](https://github.com/ovn-org/ovn/commit/cbf97bd8a85472b326b372e6c87ec96884248cc0) controller: Do not bind container port if parent is not bound.
- [3a398255](https://github.com/ovn-org/ovn/commit/3a398255290f025e2da94831379d0c0578ba2ce5) controller: Update related ports when parent of container is deleted.
- [0054ab75](https://github.com/ovn-org/ovn/commit/0054ab755e2654eb27361c3d7d9e671865494825) northd: Always commit ct.est sampled traffic in the original direction.
- [e51b449f](https://github.com/ovn-org/ovn/commit/e51b449f750628fd00fc6580d068c60c787c7315) controller: Prevent crash when db is empty.
- [3f6dde05](https://github.com/ovn-org/ovn/commit/3f6dde056dbae06bf5b15f1006c31b3e71bd9220) test: system-ovn: Fix typos in system-test
- [cf459c9d](https://github.com/ovn-org/ovn/commit/cf459c9ddac2301b60667d93540e7dd2e6cb0bad) test: ovn-northd: Fix typos in unit-test
- [dbd39a72](https://github.com/ovn-org/ovn/commit/dbd39a728196e0b30cb1bc565ba0ff8b01f7fda3) test: ovn: Fix typos in unit-test
- [20d28fcc](https://github.com/ovn-org/ovn/commit/20d28fcc33f5afd87266c2ccff4527f87b932b3e) northd: Don't generate IPv6 prefix delegation flows if not configured.
- [f90dc351](https://github.com/ovn-org/ovn/commit/f90dc351d9906e276acb6e40f2cd1fdc7d816e38) northd: Add missing multicast match to DHCPv6 options flows.
- [c8c21d91](https://github.com/ovn-org/ovn/commit/c8c21d9102ca18092dfc3c73c4d7acca5b16d5b3) northd: Populate additional-chassis to HA group.
- [0e2fb834](https://github.com/ovn-org/ovn/commit/0e2fb834f62cc5590221b995f8937d8a49a7d24d) Fix load balanced hairpin traffic for fragmented packets.
- [e5b428ec](https://github.com/ovn-org/ovn/commit/e5b428ecf61f191ae9a5a063242ccafa17946dcd) northd: Commit ct_label.obs_point_id for blocked connections.
- [b7ae22b8](https://github.com/ovn-org/ovn/commit/b7ae22b85552e49790d690130303ef8d7cac7399) tests: Wait for controller exit before restart.
- [e090b4ee](https://github.com/ovn-org/ovn/commit/e090b4ee942b65d7ffed4d1a20b6dd815625cd82) Revert "controller: Properly handle localnet flows in I+P.".
- [6448f5e3](https://github.com/ovn-org/ovn/commit/6448f5e364dc4df016f965cfd9345aed66e30dea) pinctrl: Skip non-local mac bindings in run_buffered_binding().
- [ea353473](https://github.com/ovn-org/ovn/commit/ea353473209cadb551f4b84793fdddaf6b7c3595) pinctrl: Skip deleted mac bindings in run_buffered_binding().
- [8579859f](https://github.com/ovn-org/ovn/commit/8579859f516dfa07ee38e32cdebe6930d1dd3cad) mac-cache: Properly handle deletion of SB mac_bindings.
- [33a6ae53](https://github.com/ovn-org/ovn/commit/33a6ae53f444e7e6d79fc6bad839e8d7ddeb1b31) pinctrl: Use correct map size in pinctrl_handle_put_fdb().
- [8eaa7d59](https://github.com/ovn-org/ovn/commit/8eaa7d599138b24e18a18cf8c2435da4fe34a293) controller: Fix "use after free" issue in statctrl_run().
- [ed12a2c3](https://github.com/ovn-org/ovn/commit/ed12a2c39291b224b855620f415c97e7a834ed2c) Prepare for 24.09.2.