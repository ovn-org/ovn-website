+++
title = "Changelog v23.09.2"
[_build]
  list = 'never'
+++

### Changes from v23.09.1 to v23.09.2

- [04b23938](https://github.com/ovn-org/ovn/commit/04b23938302ad54f453f622a4b0c2fa5e27d3e41) Set release date for 23.09.2.
- [215d53ea](https://github.com/ovn-org/ovn/commit/215d53ea1436f03ab26a1a65df0824b319e6a4c3) northd: Don't create fair Sb meters for ACLs with logging disabled.
- [5bf1773c](https://github.com/ovn-org/ovn/commit/5bf1773c90ef7b61a85946027a987184e8d74fa0) ci: Update crun in GitHub actions runner.
- [afa3da76](https://github.com/ovn-org/ovn/commit/afa3da7677ed4d484612b820d8f09642d5821bd4) ci: Update crun in Cirrus CI cloud image.
- [683fb6dd](https://github.com/ovn-org/ovn/commit/683fb6dd2fc3c2ab025b1dd87ba2883e40d6d775) controller: ofctrl: Use index for meter lookups.
- [c463d1de](https://github.com/ovn-org/ovn/commit/c463d1de1a0c2cd368a4809f0d9eda9792b79851) tests: Fix "router port type update and then ...".
- [cbd4f2fc](https://github.com/ovn-org/ovn/commit/cbd4f2fcd0223a96c739dd07eded753f8f9b2a30) tests: Fix "ovn-controller - Chassis other_config".
- [81486b62](https://github.com/ovn-org/ovn/commit/81486b62bcac0d081ca907533ae34d826605b485) tests: Fix "ofctrl wait before clearing flows".
- [48a08a44](https://github.com/ovn-org/ovn/commit/48a08a447340b095e8472d40aaaac5156320b4c1) tests: Fix flaky "ovn-controller-vtep - binding 1".
- [a088df5a](https://github.com/ovn-org/ovn/commit/a088df5aa75a7207ccdd751d2167e1536113737f) tests: Fix flaky "options:requested-chassis ...".
- [0a572665](https://github.com/ovn-org/ovn/commit/0a5726652b202add51d1dc8b6557268673e6cc51) tests: Fix typos in tests.
- [609a943e](https://github.com/ovn-org/ovn/commit/609a943e33c734d368f2019e7d3b41e31bb31d6f) tests: Have tests fail when adding veth peer fails.
- [511f5a21](https://github.com/ovn-org/ovn/commit/511f5a214226be84ae3b9434ffcab973e37295eb) pinctrl: dns: Ignore additional records.
- [27d23712](https://github.com/ovn-org/ovn/commit/27d23712260b9faba23018ce973010743e30ccf7) ovn-ic: Fix global blacklist filter for IPv6 addresses.
- [28b0eddf](https://github.com/ovn-org/ovn/commit/28b0eddff68c5a64b80071a9a27cb79e3fac792a) tests: Fix macro OVN_CHECK_PACKETS_CONTAIN.
- [c0c9e507](https://github.com/ovn-org/ovn/commit/c0c9e507470439c3220b99c361f71e0cff3406fc) features.c: Always wait on the rconn.
- [41e7f018](https://github.com/ovn-org/ovn/commit/41e7f01872dae61b9ffcc1d3871865313ff90619) ci: Bump CirrusCI Ubuntu image version
- [99d22a17](https://github.com/ovn-org/ovn/commit/99d22a176f45971516803129f08c7a37a50bc4a1) Documentation: Fix broken links in ovn-sandbox.rst.
- [97fca0f8](https://github.com/ovn-org/ovn/commit/97fca0f846bf6839144fc04fed6f0873198b4f89) ovn-sb.xml: Remove IPv4-only restriction from Service Monitors.
- [2981936b](https://github.com/ovn-org/ovn/commit/2981936b61e0e0694c16df979b986dd1cb60b147) github: Update versions of action dependencies (Node.js 20).
- [a36f2955](https://github.com/ovn-org/ovn/commit/a36f2955be67a6581e81fb3ae27de825e0046b52) northd: Remove the protocol match from ECMP symmetric reply flows.
- [6a4c412f](https://github.com/ovn-org/ovn/commit/6a4c412f43d5f1c076fac3784a4ffeb8a3861436) northd: Explicitly handle SNAT for ICMP need frag.
- [06984247](https://github.com/ovn-org/ovn/commit/069842478601c0b01b0cc3117637e5a00344fcb6) actions: Adjust the ct_commit_nat action.
- [f224c6e5](https://github.com/ovn-org/ovn/commit/f224c6e5f69c099ddb008f99dba2e19a902a612f) ovs: Bump submodule to tip of OVS branch-3.2.
- [7ee483a4](https://github.com/ovn-org/ovn/commit/7ee483a45df19e11e26487e64a93940e0de64b9a) actions: Use random port selection for SNAT with external_port_range.
- [0e684ec2](https://github.com/ovn-org/ovn/commit/0e684ec206e8979694912ad1037145ccd0d0b7dc) ovn-ic: Handle NB:name updates properly.
- [859e8d91](https://github.com/ovn-org/ovn/commit/859e8d917408d50272c910f78ac44ab8a593aa13) northd: Make sure that affinity flows match on VIP.
- [d39e7c00](https://github.com/ovn-org/ovn/commit/d39e7c0068ecc719a3d6154e2078d6d9a3435fc9) Fix segfault due to ssl-ciphers.
- [6d2f9d60](https://github.com/ovn-org/ovn/commit/6d2f9d60760a793c15ca7423b24ff586b653fc76) ovn: Add tunnel PMTUD support.
- [12007535](https://github.com/ovn-org/ovn/commit/120075357a624293d52a1905c47a1bd249d2157c) controller: fixed potential segfault when changing tunnel_key and deleting ls.
- [8e25c1c3](https://github.com/ovn-org/ovn/commit/8e25c1c37aa3301f69bc89ee49ffaef5aa2f76fd) northd: Use proper field for lookup_nd
- [bf334c65](https://github.com/ovn-org/ovn/commit/bf334c65e1ead50013880049564d445919aee61f) checkpatch.py: Port checkpatch related changes from the OVS repo.
- [6ce267af](https://github.com/ovn-org/ovn/commit/6ce267af7124a93306d8b5bf4944379536ecd264) actions: Make sure affinity learnt flows are auto deleted.
- [f85f5e39](https://github.com/ovn-org/ovn/commit/f85f5e3929c916985c7dfc0fe0f0433347d8bfae) pinctrl: Directly retrieve desired port_binding MAC.
- [28fef02d](https://github.com/ovn-org/ovn/commit/28fef02db946ba8113a2752e1abf61d8df5797e3) test: add dedicated test for garp-max-timeout
- [0d5e6d65](https://github.com/ovn-org/ovn/commit/0d5e6d65db19845aede9198d8e164d934a5f189e) treewide: Fix small memory leaks reported by static analysis
- [1a70f3f1](https://github.com/ovn-org/ovn/commit/1a70f3f171c032c2329bb66f2e62d233ce19a494) Documentation: Add note about pinning the container after release
- [639aff08](https://github.com/ovn-org/ovn/commit/639aff0896527f9c48c56d6dfb3fdce84403b6dd) ci: Cover more container posibilities
- [ca0f1775](https://github.com/ovn-org/ovn/commit/ca0f17758559ed836dfa0220e472ea99438cefb8) ci: Build container image before very job
- [9c97cdcd](https://github.com/ovn-org/ovn/commit/9c97cdcd757ce356a85b3e6dde7eb19776fe4c38) ovs: Bump submodule to include IDL "spurious delete" fix.
- [e9863e57](https://github.com/ovn-org/ovn/commit/e9863e57320d24f8fb0d02436834f795ba58ce48) Correct ethtype referencing incorrect values
- [ed4e4a94](https://github.com/ovn-org/ovn/commit/ed4e4a94ba44f5d5be5148ee82f336cab3adc7ec) Revert "ovn: add geneve PMTUD support"
- [20ea3b63](https://github.com/ovn-org/ovn/commit/20ea3b63fb3a2fce2c9e273bfbdcb4d8399b8091) northd: forward arp request to lrp snat on.
- [8cabb443](https://github.com/ovn-org/ovn/commit/8cabb443ae88dded5cd1800bdcea5c5760954d25) northd: fix missing port up when deleting and adding back an lsp
- [e54ec661](https://github.com/ovn-org/ovn/commit/e54ec661ef67cd93d1a72de907b37fab522bc2f9) ovn-macros: Make sure stopped daemons continue before the test ends.
- [5141c9d4](https://github.com/ovn-org/ovn/commit/5141c9d4c7c861f6a65a711e59a4e64ae7d2fcdb) system-test: Fix tcpdump usage in LB template tests.
- [49d33629](https://github.com/ovn-org/ovn/commit/49d33629595a9c7fc44d7ac86926c83e475b322d) tests: Move SCTP test from kernel only to general OVN system tests.
- [d87ffbe4](https://github.com/ovn-org/ovn/commit/d87ffbe44d5b5c3f143c1e38e868f9db636b4565) tests: Remove 'protoinfo' from the conntrack entries for SCTP tests.
- [44a40011](https://github.com/ovn-org/ovn/commit/44a40011f0b7f465c1eb60c9016bd56e09d7e538) northd: Skip transient IDL records.
- [ba7a45bd](https://github.com/ovn-org/ovn/commit/ba7a45bde1de25868e0b16d8e58e6d523e2034ab) system-tests: Consolidate wait condition in CoPP test
- [4ef375ed](https://github.com/ovn-org/ovn/commit/4ef375edc8bee094f24b9e649dc01ce3edd2034b) pinctrl: Fix up comments about sending RST packets for healthcheck.
- [e42ca82f](https://github.com/ovn-org/ovn/commit/e42ca82fb92cd69bbfd4da72b3c22bc57fc1ecd0) ovn: add geneve PMTUD support
- [b7889118](https://github.com/ovn-org/ovn/commit/b788911812171ee5d9c51806b1e287be910164c9) fmt_pkt: make sure scapy-server is started once
- [820e1175](https://github.com/ovn-org/ovn/commit/820e11754bff7b7029abf8bd8f166c169bdd8d04) fmt_pkt: improve scapy-server logging
- [2d710c3b](https://github.com/ovn-org/ovn/commit/2d710c3b1d9444a49f80db6058462e7d33253644) fmt_pkt: use -S check to wait for scapy sock file
- [fc311bb6](https://github.com/ovn-org/ovn/commit/fc311bb6d6108d49b356d9c785f6d47e7dc8faff) fmt_pkt: don't subshell when calling ovs-appctl
- [acc63727](https://github.com/ovn-org/ovn/commit/acc63727d14ff7e9f447ed90115f74235f968499) controller: fix group_table and meter_table allocation
- [8a000cc8](https://github.com/ovn-org/ovn/commit/8a000cc863773030828a4cda2167840f08c4a65c) Prepare for 23.09.2.