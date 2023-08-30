+++
title = "Changelog v20.03.2"
[_build]
  list = 'never'
+++

### Changes from v20.03.1 to v20.03.2

- [034d3570](https://github.com/ovn-org/ovn/commit/034d35707024bdac982310af2fac2528c2d32f2c) Set release date for 20.03.2.
- [bf4d2043](https://github.com/ovn-org/ovn/commit/bf4d20434159a1793016cbdfc1eee1d25a306c1b) pinctrl: Don't send gARPs for localports
- [29548040](https://github.com/ovn-org/ovn/commit/295480407837cf9812cfb9fbcbd23a844ac6bd0e) ci: Fix handling of python packages.
- [36a8b1a1](https://github.com/ovn-org/ovn/commit/36a8b1a1d9bc1d087df0c2791c3363f240b84799) northd: Add Controller_Event RBAC rules
- [8d7c73cc](https://github.com/ovn-org/ovn/commit/8d7c73cc031c18903f0c9f7e1dc535c2a193284f) northd: Amend Chassis RBAC rules
- [4d83a056](https://github.com/ovn-org/ovn/commit/4d83a056d9bc7b1f64ef26748cd404711209b728) northd: Amend RBAC rules for Port_Binding table
- [bc9d6611](https://github.com/ovn-org/ovn/commit/bc9d6611ba4f8e0d495f574fe09ff5ab6e9af66e) ovn-ctl: Handle cluster db upgrades for run_(nb/sb)_ovsdb
- [1f2df9ec](https://github.com/ovn-org/ovn/commit/1f2df9ec3a5961f5d3159bced14311aa833c2b49) Revert "ovn-ctl: Handle cluster db upgrades for run_(nb/sb)_ovsdb"
- [2283617a](https://github.com/ovn-org/ovn/commit/2283617adc564164b9655187c505c9558e67db33) ofctrl: Fix the assert seen when flood removing flows with conj actions.
- [824249dc](https://github.com/ovn-org/ovn/commit/824249dc2b616e62089c9038e18da149a3494bb9) ofctrl: Do not link a desired flow twice.
- [4b6dc713](https://github.com/ovn-org/ovn/commit/4b6dc713c5fb5790b135cdd6606b6893117a3fe8) ofctrl: Fix the assert seen when flood removing flows.
- [0ef44958](https://github.com/ovn-org/ovn/commit/0ef44958bb1c28721dc86aa21757077fc0b24c12) tests: Fix test "ovn -- Superseding ACLs with conjunction".
- [d3ae7ebe](https://github.com/ovn-org/ovn/commit/d3ae7ebef13ca6b2648f22cac1d73c519573dc76) tests: Add ofctl_strip_all() to filter OVS flow outputs.
- [e868c78b](https://github.com/ovn-org/ovn/commit/e868c78bd7bdbd39e34f126524c1fa7ce03e8fd8) ovn.at: Make some of the tests more predictable.
- [0280878a](https://github.com/ovn-org/ovn/commit/0280878addd9d852449ee9ee6bf2d7e5461ff7e5) ofctrl.c: Add a predictable resolution for conflicting flow actions.
- [d11e11cc](https://github.com/ovn-org/ovn/commit/d11e11cca987618cf544942e8ae62f4d64a1bf08) ofctrl.c: Always log the most recent flow changes.
- [589e5227](https://github.com/ovn-org/ovn/commit/589e5227572e9da9593664eeea4e6c8ac82be9f3) ofctrl.c: Simplify active desired flow selection.
- [fa08a1a1](https://github.com/ovn-org/ovn/commit/fa08a1a155c6538c672714b57aa9aa2749352c4f) ofctrl.c: Do not change flow ordering when merging opposite changes.
- [2cff4639](https://github.com/ovn-org/ovn/commit/2cff4639076b1d719db6ff3b480d9ed7468fc816) ofctrl.c: Only merge actions for conjunctive flows.
- [ebf1929b](https://github.com/ovn-org/ovn/commit/ebf1929bd48cb05c961a6b8bbdb02598435d1c68) ofctrl.c: Avoid repeatedly linking an installed flow and a desired flow.
- [0c388ade](https://github.com/ovn-org/ovn/commit/0c388ade25e3cb0f8f322680df15707231a206e5) ofctrl.c: Fix duplicated flow handling in I-P while merging opposite changes.
- [d7cb15d3](https://github.com/ovn-org/ovn/commit/d7cb15d333aef3ee9f1db0f0860c4ee9e345e70c) ofctrl.c: Merge opposite changes of tracked flows before installing.
- [a4809a59](https://github.com/ovn-org/ovn/commit/a4809a59175903a7276b3ca6d36a23dabb5fa363) ofctrl: Incremental processing for flow installation by tracking.
- [c17b73d1](https://github.com/ovn-org/ovn/commit/c17b73d172139b9395595d86cf4d3309c2207ca9) ofctrl.c: Refactor - move openflow msg construction to functions.
- [cc68620a](https://github.com/ovn-org/ovn/commit/cc68620af4d2b0b5fb6e7ebb8d1b781830e56df1) ofctrl.c: Maintain references between installed flows and desired flows.
- [f56d6421](https://github.com/ovn-org/ovn/commit/f56d6421ffedbc8111447edb61a571fa7ebef5b1) Revert "Manage ARP process locally in a DVR scenario"
- [dce49ab7](https://github.com/ovn-org/ovn/commit/dce49ab7bf0365e50e9660098f743b340d444fbe) ovn-ctl: Handle cluster db upgrades for run_(nb/sb)_ovsdb
- [aa8ef558](https://github.com/ovn-org/ovn/commit/aa8ef5588c119fa8615d78288a7db7e3df2d6fbe) northd: Fix ha_chassis_group txn error for external ports.
- [0c26bc03](https://github.com/ovn-org/ovn/commit/0c26bc03064f2c21d208f0f860b48d8ab39380cb) ovn-northd: Don't add arp responder flows for lports with 'unknown' address.
- [17d77346](https://github.com/ovn-org/ovn/commit/17d77346bab7e55f2f8f5fc712898a995ca81f3a) sandbox: Fix path to Sb DB socket for ovn-controller-vtep.
- [cc13684b](https://github.com/ovn-org/ovn/commit/cc13684bbe75e08e138b8b69151acb1f0a7adff3) northd: Fix duplicate logical port detection.
- [c554284d](https://github.com/ovn-org/ovn/commit/c554284d394141d414814ef5222145830d8ba7dc) tests: Introduce new testing helpers.
- [847589ad](https://github.com/ovn-org/ovn/commit/847589adf8d31d7e9d735696f9e01a418f8b2cbe) ovn-trace: fix trigger_event warning.
- [dd9188d7](https://github.com/ovn-org/ovn/commit/dd9188d74539a0217b25c0d773aca7c3a15af3ee) pinctrl: Fix race condition when explicitly clearing IGMP groups.
- [74b522d6](https://github.com/ovn-org/ovn/commit/74b522d6ec85a38e33fce433c7e07c603a6d6979) ovn-nbctl: fix sigsegv when nexthop arg is missing
- [b0ee5d5a](https://github.com/ovn-org/ovn/commit/b0ee5d5ae2389cfae2c6b8728ed5e12cd57bfe8c) github: Fix Ubuntu package installation.
- [efb18e69](https://github.com/ovn-org/ovn/commit/efb18e69493a777fcfa97ce33a3e7293b771dbd8) chassis: Do not try to guess system-id changes.
- [5ee02c78](https://github.com/ovn-org/ovn/commit/5ee02c787531ab4bdd5caa460aac3b1835dc7f4d) CI: Fix compilation errors for osx builds.
- [391c49a3](https://github.com/ovn-org/ovn/commit/391c49a3ca1613276a56637375aadeba57f65fd2) CI: Add github actions workflow.
- [d25a5adf](https://github.com/ovn-org/ovn/commit/d25a5adf1856fc0d09c6be286295de6083a5f5de) ovn-controller-vtep: Fix leak of multicast macs.
- [d874214c](https://github.com/ovn-org/ovn/commit/d874214cf2220c83b4549da1a652d02c1047b5e7) pinctrl: Fix race condition when accessing br_int_name.
- [cbbd7e1f](https://github.com/ovn-org/ovn/commit/cbbd7e1f1973c5e8beb8ac392c692f5122257a66) ovn-nbctl: Fix double-free of parsed commands on error path.
- [4ae9104b](https://github.com/ovn-org/ovn/commit/4ae9104bacfc1c7d9ce1ad220468810d564aa447) utilities: Free argv returned by ovs_cmdl_env_parse_all().
- [d0c3a25b](https://github.com/ovn-org/ovn/commit/d0c3a25b5e6118ff8212a152e3a50cb7379d8179) ovn-nbctl: Cleanup allocated memory to keep valgrind happy.
- [8fe336ac](https://github.com/ovn-org/ovn/commit/8fe336ac3ca4dc1200c8566c59b720a83c381c21) actions: Fix leak of dynamic string on fwd group encoding failure.
- [531d8832](https://github.com/ovn-org/ovn/commit/531d8832db4b8853d4c60ec0aabfe9dbb2c51849) northd: Fix leak of dynamic string for fwd group ports.
- [dd94424d](https://github.com/ovn-org/ovn/commit/dd94424d8664ead76bc6352af68906bbe71137aa) ovn-nbctl: Fix error leak on duplicated switch port.
- [2b360113](https://github.com/ovn-org/ovn/commit/2b3601132d9a408f6e2b9dffd3b48c8c531862e2) ovn-controller: Fix leak of pending ct zones.
- [79698908](https://github.com/ovn-org/ovn/commit/79698908674136da774dca1f0b0642c49bbe1e32) pinctrl: Fix leak of DNS cache records.
- [f749033a](https://github.com/ovn-org/ovn/commit/f749033a3c71e1c4972075c3321e6b28784a719e) ofctrl: Fix leak of meter mod bands.
- [1743aedc](https://github.com/ovn-org/ovn/commit/1743aedc104d66c965e7276b91aaa964f0c8ffce) actions: Fix leak of select group members.
- [01564e90](https://github.com/ovn-org/ovn/commit/01564e904d584a7a7d4600ab237648702ba49a70) actions: Fix leak of child ports in fwd group.
- [26483a22](https://github.com/ovn-org/ovn/commit/26483a2262325007883ec879b9a990f3d9c7f72c) ovn-detrace: Only decode br-int OVS interfaces.
- [06ea7054](https://github.com/ovn-org/ovn/commit/06ea7054213d89cfea67b985a1752c58aeef30a3) pinctrl: Fix memory leak when handling empty lb backends.
- [ad8a9904](https://github.com/ovn-org/ovn/commit/ad8a99045a39e7f50e54e703b493317b9dfad07e) pinctrl: Fix memory leak in controller_event_run().
- [84ac6861](https://github.com/ovn-org/ovn/commit/84ac6861b016d59ad97291fa538529773b054aad) ovn-ic: Fix route hash.
- [d9e1501f](https://github.com/ovn-org/ovn/commit/d9e1501f64392693c8bdbb1ff20c6b810799d9e1) ovn-northd: Skip conntrack for MLD packets.
- [28ed6c1f](https://github.com/ovn-org/ovn/commit/28ed6c1f92f06676987a1046a01738b903ae616e) ovn-controller: Fix conjunction handling with incremental processing.
- [9e6d7098](https://github.com/ovn-org/ovn/commit/9e6d7098da74761df03a67a23df9407c101845ac) ovn.at: Fix AT for conjunction case.
- [352afbfe](https://github.com/ovn-org/ovn/commit/352afbfebc4b0130baa486e717731baf478c66e2) ofctrl: change ofctrl_dup_flow to module internal function
- [c9fbb4b2](https://github.com/ovn-org/ovn/commit/c9fbb4b27ea9e0d3256031eddd8d62edf0b5ca15) pinctrl: Fix incorrect warning message for multicast querier.
- [028d6db3](https://github.com/ovn-org/ovn/commit/028d6db38ff56018ba40b3abb3da94ba7a724ffa) ovn-controller: Disable ofctrl probe by default.
- [7b58d849](https://github.com/ovn-org/ovn/commit/7b58d84909770bb91b17a91f2f3cd5456651585c) ovn-northd: Fix memory leak in build_lswitch_rport_arp_req_flows().
- [b7515245](https://github.com/ovn-org/ovn/commit/b75152453da1b714bf864d8bd6fd921f5b06926d) ovn-controller: Fix the memory leak in ref lflow handling.
- [43246e37](https://github.com/ovn-org/ovn/commit/43246e3726de28f047968b9cbd5365d586c6d5d1) ovn-northd: Fix the missing lflow issue in LS_OUT_PRE_LB.
- [5bc34b79](https://github.com/ovn-org/ovn/commit/5bc34b7989d0fac97c3d594872654bf4cb185505) northd: set packet length in check_pkt_larger()
- [6b3c3c44](https://github.com/ovn-org/ovn/commit/6b3c3c44a17e2d13dd66e1b575272a11a1118fc0) Honour router_preference for solicited RA
- [7ed6b19a](https://github.com/ovn-org/ovn/commit/7ed6b19a3b0b0c9a33d35fba30e9681d7a4c6870) Fix ovn-controller generated packets from getting dropped for reject ACL action.
- [53285ae3](https://github.com/ovn-org/ovn/commit/53285ae3d99fe73e97ac6eba87c987c10f2971ce) northd: By pass IPv6 Router Adv and Router Solicitation packets from ACL stages.
- [7d4a8b97](https://github.com/ovn-org/ovn/commit/7d4a8b9759c0e3808b8960c6aff5b05c671ce88a) Prepare for 20.03.2