+++
title = "Changelog v25.03.1"
[_build]
  list = 'never'
+++

### Changes from v25.03.0 to v25.03.1

- [4b8dac64](https://github.com/ovn-org/ovn/commit/4b8dac64fd3fbbfb39a7105365d5143c7ffa5a35) Set release date for 25.03.1.
- [f751ea8a](https://github.com/ovn-org/ovn/commit/f751ea8a6a0c767993230b664f90ff9dc208b9ca) multinode: Fix "HA: Check for missing garp ... ".
- [a9aa3a91](https://github.com/ovn-org/ovn/commit/a9aa3a91d188ef63981d910a768c7de32ad1bbae) multinode: Fix removing databases.
- [54ec9124](https://github.com/ovn-org/ovn/commit/54ec9124ef8f895b42c8e50558e677a016025bf8) system-ovn.at: Fix 'load-balancer and firewall tuple conflict' tests.
- [59879936](https://github.com/ovn-org/ovn/commit/59879936a795945bf298d96e6a782d5f4761c777) controller: Add en_route_exchange_status I-P node.
- [cec627ba](https://github.com/ovn-org/ovn/commit/cec627ba0306d9bc9bd647f0d9e78262250a5573) controller: Take into account nl failures updating VRF and configured routes.
- [afa60132](https://github.com/ovn-org/ovn/commit/afa60132080fa966bfb673905f0a72017b700ff3) en-advertised-route-sync: Advertise routes for all NAT/LB IPs owned by routers.
- [fe1c8a0a](https://github.com/ovn-org/ovn/commit/fe1c8a0a4fcbec7cd3e192cc571411b1cc77866d) ci: Bump Fedora image versions.
- [8f818c3d](https://github.com/ovn-org/ovn/commit/8f818c3d616f40930c10e014a69e08a30b7f6dc2) multinode: Adjust the ping check.
- [28c1cdde](https://github.com/ovn-org/ovn/commit/28c1cddeb8b088948c31c293756c3e736cc334da) system-test: Prevent flakiness of "virtual port with floating IP" test.
- [1a3b8a60](https://github.com/ovn-org/ovn/commit/1a3b8a601ebb5f09bf53819191d1ea69fbe70cc5) ovs: Bump submodule to get compilation fixes.
- [4e2b72c0](https://github.com/ovn-org/ovn/commit/4e2b72c0e218351773c372b37065c8178d7ab98b) ci: Disable apparmor for test runs.
- [e65402bf](https://github.com/ovn-org/ovn/commit/e65402bff6e9ec260cd1b997a077f6f565cd2d75) multinode tests: Add HA test checking for GARP.
- [905cc882](https://github.com/ovn-org/ovn/commit/905cc882ec8ef9c698f69f06ddba8d0b356bbc00) multinode tests: Update macros for cleaner exit.
- [8ab8570e](https://github.com/ovn-org/ovn/commit/8ab8570e21ffe7f7923d3b9cda25070d7d39f5d6) pinctrl: Fix missing garp.
- [89339e67](https://github.com/ovn-org/ovn/commit/89339e670e2a23a61555fc75f8a02ef52a3e6c89) binding: Avoid 100% CPU when postponing claims.
- [ca388ad6](https://github.com/ovn-org/ovn/commit/ca388ad68f6f4c3c93fcc2a46b8a800562b430b1) controller: Fix advertised_route incremental handler.
- [95f11755](https://github.com/ovn-org/ovn/commit/95f11755665f97c12dbaf03cdbfd158f42060686) route-exchange-netlink: Remove unused re_nl_dump() declaration.
- [6d5c6d70](https://github.com/ovn-org/ovn/commit/6d5c6d70afa214e908956493f058d6307678d3fc) northd: Sample_Collector.set_ids can actually be 32-bit values.
- [86ca67c9](https://github.com/ovn-org/ovn/commit/86ca67c9782a9054518cd981dc7ea7fdbb3440f2) tests: Added missing package dependency check.
- [ddb38407](https://github.com/ovn-org/ovn/commit/ddb38407e95c60e1166982280866ba6ddc579249) cksum: Added checksum for pipeline stages.
- [2399c10e](https://github.com/ovn-org/ovn/commit/2399c10e97a9c4f58808e792b2e9877bdb5eb54c) ic: Fix lrp and lsp orphan route learn or advertise.
- [362d2c0b](https://github.com/ovn-org/ovn/commit/362d2c0b9bc13da031c08497504c2601b5de6897) tests: Don't assume first bucket will be chosen.
- [5c32795e](https://github.com/ovn-org/ovn/commit/5c32795e0745897d6e6fcd9a33b9c523f5ebe919) ci: Add permanent fix for /etc/hosts file.
- [30717870](https://github.com/ovn-org/ovn/commit/30717870c70dac547a8bd92b35010cc74dfbbbe8) pinctrl: Remove useless volatile qualifier.
- [65ae5bef](https://github.com/ovn-org/ovn/commit/65ae5bef3db049648804535e63a72a06dbce48cc) tests: Add direct lsp to dynamic-routing tests.
- [2a77e723](https://github.com/ovn-org/ovn/commit/2a77e7230fd72ce705ac1c2ffc071f4ca20f4bb5) ovn-controller: Update handlers for route changes.
- [0a9906c8](https://github.com/ovn-org/ovn/commit/0a9906c82158d829fb8052d764a93825ea2bc9ee) route: Filter datapaths that should advertise.
- [74542136](https://github.com/ovn-org/ovn/commit/7454213615258cc445ce7e49f9d50c6c5abfbc7b) northd: Set REGBIT_CONNTRACK_COMMIT earlier.
- [9f1c2b14](https://github.com/ovn-org/ovn/commit/9f1c2b14a0ba300e1719d57f62ebf1c060d63c35) contoller, northd: Limit number of claims for virtual ports.
- [81c5e016](https://github.com/ovn-org/ovn/commit/81c5e0168c6c0fc98c3bb64a43aa1561d7900dfe) controller: Remove only commited virtual port binding requests.
- [2f6cf633](https://github.com/ovn-org/ovn/commit/2f6cf63351c0bbc2637f0a7713eec4689a9b283b) controller: Make sure we will update routes on tracked port change.
- [58735ad2](https://github.com/ovn-org/ovn/commit/58735ad207803aa9c5d6cd236dc9aafab83c18c6) northd: Prevent SB LB duplicates.
- [4b7392d1](https://github.com/ovn-org/ovn/commit/4b7392d1a467f1de51d4bf869f534d2d29b485d1) tests: Fix racy hard_age value.
- [2c98b6c1](https://github.com/ovn-org/ovn/commit/2c98b6c13464ddb7c1ad40c49df4d806b6a76073) tests: Prevent flakiness of "LR ct-commit-all" test.
- [b4a897ac](https://github.com/ovn-org/ovn/commit/b4a897ac0aeec16b01eb64b52d7ff0df40081a6a) ovn-nb: Improve docs for nbctl --template lb-add.
- [5713cd60](https://github.com/ovn-org/ovn/commit/5713cd605f5012d06135f302de7bcf42affedbb2) ovn-nbctl.8: Document the "--route-table" option.
- [eabf8251](https://github.com/ovn-org/ovn/commit/eabf8251ca3ee537c9facd3d1986ab82b6b84a02) ovn-architecture.7: Fix outdated nb_cfg description.
- [df4e4bf2](https://github.com/ovn-org/ovn/commit/df4e4bf291f396234b29e15ee68110545a741243) tests: Don't hardcode table numbers in the default flows test.
- [5ad811ce](https://github.com/ovn-org/ovn/commit/5ad811ce400838c4d024fb23fc3b1ee66944c78a) controller: Optimize adding 'dps' to the local datapaths.
- [4e7f4a1e](https://github.com/ovn-org/ovn/commit/4e7f4a1e4c6d00382d7880eb4aa73e1db9ca3102) controller: Expand the helper lport_get_peer().
- [354c4b29](https://github.com/ovn-org/ovn/commit/354c4b298516ad1ee45bc1a40f575b701a81c91d) controller: Add a helper lport_get_cr_port().
- [77f6069e](https://github.com/ovn-org/ovn/commit/77f6069e891df4bd96f4285149f5417d1c4fdf26) controller: Add debug/dump-local-datapaths unixctl.
- [5a12b937](https://github.com/ovn-org/ovn/commit/5a12b937f1a035d926842b72730656776d4ab8cf) northd: Avoid matching on ct_state.dnat in logical flows.
- [87f8d012](https://github.com/ovn-org/ovn/commit/87f8d012aeae27f0e47066d508ea9b2278d5ee63) lib: northd: Add a new ct-state-save feature flag.
- [001ba9a3](https://github.com/ovn-org/ovn/commit/001ba9a3ae1a55d41ebd5958f8f944821205bd55) lib: ovn-controller: Add a new ct_state_save() logical action.
- [fe5740e2](https://github.com/ovn-org/ovn/commit/fe5740e2c75fdb815a1dec7d812e88694727d366) northd: Limit flooding the self originated neigh disc packets.
- [4b41c118](https://github.com/ovn-org/ovn/commit/4b41c118a01a715201937f9279bd95cf562bef70) northd: Fix network_id computation for IPv6 LRP networks.
- [1d7951c3](https://github.com/ovn-org/ovn/commit/1d7951c3cedc82d32e922cb01659ae1f9c1a213a) ovn-nbctl: Add --template option for lb-add.
- [d5b6169d](https://github.com/ovn-org/ovn/commit/d5b6169d3ffc566dca7d8a34e1e89fd85b1b8ddb) tests: Use scapy contrib BFD implementation.
- [202a2a86](https://github.com/ovn-org/ovn/commit/202a2a8675e9030b97d5d21ba50ec1008139c346) controller, northd: Add command to enable time warp.
- [40b7ffe7](https://github.com/ovn-org/ovn/commit/40b7ffe7a0b41eda468f800dc113413eebe9663f) docs: Fix up stage-hint ovn-sb documentation.
- [2326d64f](https://github.com/ovn-org/ovn/commit/2326d64f48ad3f8f103a3238a8154bc8529a0465) northd: Do not drop ip traffic with destination vip expressed via template vars.
- [6756ece3](https://github.com/ovn-org/ovn/commit/6756ece392bafcc2e2041369e0dfffb377f8d9e7) northd: Use next-hop network for SNAT when lb_force_snat_ip=router_ip.
- [d0143b75](https://github.com/ovn-org/ovn/commit/d0143b75379761ed8a927b9bc6b66b9446076cf8) ovs: Update the submodule to include python F824 fix.
- [bd4c1eee](https://github.com/ovn-org/ovn/commit/bd4c1eee96aa3fd6d4f5e294dcab604a45e54f6d) ci: Add missing llvm package into Fedora.
- [664a82ee](https://github.com/ovn-org/ovn/commit/664a82eeb830f284ee5fdfc941f399a78e88f3f0) controller: Redirect traffic for container port.
- [e07c56c4](https://github.com/ovn-org/ovn/commit/e07c56c430be705452cfd083741e4d21b9c47042) multinode tests: Simplify/Cleanup migration test.
- [1a3fd5de](https://github.com/ovn-org/ovn/commit/1a3fd5de519b962769a5b377ff7bdc674fa4068e) lb: Make the LB validation consistent.
- [5e2b1ecf](https://github.com/ovn-org/ovn/commit/5e2b1ecf945b1124c4593ea76a86cd81bfbc6a9b) tests: Ignore FDB transaction errors.
- [65e7bcbf](https://github.com/ovn-org/ovn/commit/65e7bcbf2bc2673262c621bd714d0e8c3e855b78) controller: Fix possible NULL ptr access in lport_is_local().
- [e664d16d](https://github.com/ovn-org/ovn/commit/e664d16d03aaeac963c203d455794d94a21978ae) controller: Fix active mac-binding refresh for IPv6.
- [4a8b656a](https://github.com/ovn-org/ovn/commit/4a8b656a2ad650a28c6e181c507a4326c2725290) tests: Fix flaky "IGMP incremental processing".
- [d3adc824](https://github.com/ovn-org/ovn/commit/d3adc824a28e3a19fa1067f2be4c978516c89d94) tests: Avoid adding two similar load balancers.
- [a4a71fca](https://github.com/ovn-org/ovn/commit/a4a71fcad105e32fa09fd330b9e8b06c2f565614) Fix missing load balancer hairpin flows.
- [c6af3c56](https://github.com/ovn-org/ovn/commit/c6af3c568813f10f4971ebe7ac0fabcb0f838225) ovn.at: Run 'ACL Conntrack ID propagation' for each northd type.
- [06b49b45](https://github.com/ovn-org/ovn/commit/06b49b45633cae02c9060e0fa0d799514cd7aa67) ci: Bump the Ubuntu image to 24.04.
- [ea9d0982](https://github.com/ovn-org/ovn/commit/ea9d0982fa08a76c36f7e611936d30fb2edf7e15) docs: Move "Transit Router" notes to the "Logical_Router" section.
- [0cb2b9b2](https://github.com/ovn-org/ovn/commit/0cb2b9b2be9a6efb91fb4e6992e33251840a2884) containers: Get sparse from the official GitHub mirror.
- [31cd9fca](https://github.com/ovn-org/ovn/commit/31cd9fca19f99064c8efc07fe28ea9506eaa6aad) Prepare for 25.03.1.