+++
title = "Changelog v25.09.1"
[_build]
  list = 'never'
+++

### Changes from v25.09.0 to v25.09.1

- [e20dcfd6](https://github.com/ovn-org/ovn/commit/e20dcfd6052ccef9692ca28edfd6ca8a09c5774f) Set release date for 25.09.1.
- [bfeedcce](https://github.com/ovn-org/ovn/commit/bfeedccef41de694fddea680a08b2c1af85da1e9) northd: Use dynamic_bitmap for ovn_dp_group bitmap.
- [ada2b45b](https://github.com/ovn-org/ovn/commit/ada2b45b438fc4657eef849df68bf226c2bd6d63) northd: Use dynamic_bitmap for ovn_lflow bitmap.
- [32bc9c5d](https://github.com/ovn-org/ovn/commit/32bc9c5dc08c67844259626158b6dc657ae3b12c) util: Improve dynamic_bitmap APIs.
- [0867b289](https://github.com/ovn-org/ovn/commit/0867b289503e58ac9fcd61f3ed256e8b9f0e2d42) util: Fix dynamic_bitmap_alloc routine.
- [20f64807](https://github.com/ovn-org/ovn/commit/20f64807423b81c3a3f0729fa602328e96fc9a76) northd: Introduce dynamic_bitmap struct.
- [878cda97](https://github.com/ovn-org/ovn/commit/878cda97d0255696332d1222d523c5c5bfbffc5f) northd: Skip check_pkt_larger action for ARP.
- [a5f197c7](https://github.com/ovn-org/ovn/commit/a5f197c7e1f5ff4e1ebdee028211a76492eb2514) tests: Make the ACL Sampling test more reliable.
- [f6921266](https://github.com/ovn-org/ovn/commit/f69212666223163dfb593767f9b75a2f8c41b617) ovs: Update submodule to v3.6.1.
- [02a52e90](https://github.com/ovn-org/ovn/commit/02a52e905127c0937dddad5115b1142c690c2381) ofctrl: Prevent duplicate desired flow references.
- [4d75dd9e](https://github.com/ovn-org/ovn/commit/4d75dd9efcd6c26b5cacab19ab52c93e893e4dcd) controller: Prevent transaction error for BGP routes.
- [e095ef56](https://github.com/ovn-org/ovn/commit/e095ef568ff948c69c901777e1fb716a25160685) system-test: Make sure we can bind the virtual port right away.
- [d8c305c5](https://github.com/ovn-org/ovn/commit/d8c305c5cd7585ba0f53cbacb356f36e859bd197) encaps: Properly cleanup EVPN tunnel ports.
- [b9db5287](https://github.com/ovn-org/ovn/commit/b9db5287e310070446998aa786d0c61a00d91475) northd: Fix connection tracking for enable-stateless-acl-with-lb option.
- [c6c69a34](https://github.com/ovn-org/ovn/commit/c6c69a3487222648043b2c0a3ecd12afaf0cec2c) controller: Fix handling of local/non-local routes to be advertised.
- [60f61707](https://github.com/ovn-org/ovn/commit/60f61707e94e0d401d9f0e62e182a76756bcb6dc) controller: Prevent other chassis with same encap IP.
- [e7d0bdf9](https://github.com/ovn-org/ovn/commit/e7d0bdf9e53a671da861efd3647fe665016745f8) northd: Fix virtual port ip advertisment via BGP.
- [326a478e](https://github.com/ovn-org/ovn/commit/326a478ea2c3679685774190a75fb39ef4951b06) multinode.at: Fix typo "an flat".
- [eda58f52](https://github.com/ovn-org/ovn/commit/eda58f5263e7e43fe7186476d853963f2163db60) tests: Fix command line break alignment.
- [297b7124](https://github.com/ovn-org/ovn/commit/297b7124b8dbb320ca55961c85b789a2a2273881) ovn-nb: Clarify requirements for transit router ports in our docs.
- [6ef97952](https://github.com/ovn-org/ovn/commit/6ef97952ca678013f3d6c13458a3a3b224a7e9f5) northd: Add missing RBAC rules for Learned_Route table.
- [9280620c](https://github.com/ovn-org/ovn/commit/9280620c2066f482c2cefba06a307918c393f0bf) controller: Prevent ovn-controller looping with invalid table_id set.
- [989d1576](https://github.com/ovn-org/ovn/commit/989d1576a3b5903b94455280800fe5a323a88c24) controller, northd: Add support for CMS to specify the vrf table_id.
- [7ee77d18](https://github.com/ovn-org/ovn/commit/7ee77d1892c460865a1a7552971348e1fcf99f11) route: Fix races between interface binding and dynamic route handling.
- [69a89e7f](https://github.com/ovn-org/ovn/commit/69a89e7f426868549f6f0e2b3564a9403736d60f) expr: Use prefixes instead of single bit masks for inequality.
- [56413dcd](https://github.com/ovn-org/ovn/commit/56413dcd4e2bbc387382cf3057b8ec53ca745436) ovn-dbctl: Don't access uninitialized memory on the error path.
- [f559e591](https://github.com/ovn-org/ovn/commit/f559e591aa2afef2fe40b66a741b16f8ce370094) tests: Add missing --wait options.
- [a5c2ec78](https://github.com/ovn-org/ovn/commit/a5c2ec78f3ae8d628b1a21a1b4470547fc599ed9) tests: Replace router and localnet port definitions with the helper commands.
- [0e59e79d](https://github.com/ovn-org/ovn/commit/0e59e79d2bc3773eb42fd7ddafe9c81f9396fe5c) ovn-nbctl: Add two new helper commands.
- [b5f5e0f9](https://github.com/ovn-org/ovn/commit/b5f5e0f9cf58a4062a3709b237d152127eba445f) ci: ovn-kubernetes: Enable "External Gateway" ovn-kubernetes CI lanes.
- [3fcfbb99](https://github.com/ovn-org/ovn/commit/3fcfbb9907fd0ff403a13c49c049be6963f8efd7) controller: Fix memory leak in evpn_binding_run().
- [1a748921](https://github.com/ovn-org/ovn/commit/1a7489211ea30fb67815f14c122903b90588dc64) northd: Ensure unicast ARPs are forwarded properly.
- [ce15fa4b](https://github.com/ovn-org/ovn/commit/ce15fa4b5fc73c19a583b694709e8146b5f8afe3) multinode.at: Split BGP helpers into setup/configure steps.
- [66f55671](https://github.com/ovn-org/ovn/commit/66f556711f518d8f12a2440c1796f8d8418cfad9) multinode.at: Ensure MAC/IPs on bridges used for BGP tests.
- [5690e4e1](https://github.com/ovn-org/ovn/commit/5690e4e1a590353868a7da9edb7e66d3371eb1f4) controller/neighbor-exchange: Fix learning of remote VTEPs.
- [d16d9a1c](https://github.com/ovn-org/ovn/commit/d16d9a1c14e736fe5ff5a62e7f880ed92227b485) tests: Fix flaky "ECMP symmetric reply" system test.
- [93d20610](https://github.com/ovn-org/ovn/commit/93d20610023d784cbb0cc59cccdf6773b7dc783c) system-tests: Ensure test interfaces are always deleted.
- [2d7b6b52](https://github.com/ovn-org/ovn/commit/2d7b6b52bb67327ab86b537f0bb0edde21c5425b) system-tests: Remove unused common system macros.
- [0bb60da6](https://github.com/ovn-org/ovn/commit/0bb60da63ccd810073952ef693560db43fca7de0) controller: Don't use the split buf action.
- [b3e9a427](https://github.com/ovn-org/ovn/commit/b3e9a4271fcda5ae9453d09d4970b412a4c1c0a7) tests: Simplify "MAC binding aging - probing GW router Dynamic Neigh"
- [518f7968](https://github.com/ovn-org/ovn/commit/518f7968b4d1ac7c7b4477656878a98d1e3b1a0e) northd: Remove unused mirror rule table references.
- [d6917f6d](https://github.com/ovn-org/ovn/commit/d6917f6d32bbba15019ce6171edcfee61b31afd3) ic: Fix route learning for backward compatibility to >=23.09.
- [5e1618c0](https://github.com/ovn-org/ovn/commit/5e1618c09a96f50e23c8b81cb2bfda8e11b2dde9) northd: Introduce disable_garp_rarp option for logical_router table.
- [8b350f58](https://github.com/ovn-org/ovn/commit/8b350f58ae4705785fc4b76155ce4e936fd3bf61) controller: Make sure we also match EVPN FDB on vni.
- [6fcad2ca](https://github.com/ovn-org/ovn/commit/6fcad2ca35041253651326150b46cea2acd35ff8) northd: Keep forwarding BFD traffic to router pipeline if OVN manages BFD routes.
- [b325d702](https://github.com/ovn-org/ovn/commit/b325d7023fba6933197ba4c70a6ddfd1e341dcec) test: Check BFD routes are properly announced by ovn-controller.
- [b6ba6a6a](https://github.com/ovn-org/ovn/commit/b6ba6a6ae20c220c4af01301868d83384c305570) controller: Unable to allocate meter id.
- [d702b0ed](https://github.com/ovn-org/ovn/commit/d702b0ed154a2aec94c110304ae82668b47d1a49) northd: Avoid committing DNAT traffic to SNAT zone.
- [c3545d7c](https://github.com/ovn-org/ovn/commit/c3545d7c06545640e6edc518316c99c23aec1427) tests: Added NS_CHECK_CONNECTIVITY macro.
- [e4b60f1b](https://github.com/ovn-org/ovn/commit/e4b60f1bee4eb1466362c29a82e90ac3c842a8a0) ci: Increase the multinode test timeout.
- [8ee3b244](https://github.com/ovn-org/ovn/commit/8ee3b244d4ffccba2be400f3f6bb0b7cd2d162c3) northd: Avoid reparsing LRP networks when advertising connected routes.
- [a6b5a22a](https://github.com/ovn-org/ovn/commit/a6b5a22af4813ab30742824e75f4f04048bf79bb) system-ovn: Fix the workloads in the 'dynamic-routing - EVPN' test.
- [d76d6fea](https://github.com/ovn-org/ovn/commit/d76d6feabb340a5e504893d95f2c4c739781cf07) northd: Fix receiving NA on non resident chassis.
- [894048fe](https://github.com/ovn-org/ovn/commit/894048fe093f9bcacbc6a479e00d30cfc34eff79) tests: Also remove patch ports when cleaning up resources.
- [a84b423f](https://github.com/ovn-org/ovn/commit/a84b423f0e2a5f1abc62012604a2cc7446d7ec59) controller: Do not assign pointer to bool.
- [dc7d45b1](https://github.com/ovn-org/ovn/commit/dc7d45b15a89eae5cca4a204931f95d127418d0f) neighbor-exchange-netlink: Fix misleading ne_is_valid_static_fdb() comment.
- [56819f04](https://github.com/ovn-org/ovn/commit/56819f04166bba07e5b92b71ddb9e7e712fcb225) northd: Prevent ovn-nbctl --wait=sb from returning early.
- [778466e9](https://github.com/ovn-org/ovn/commit/778466e9a5c18e0a21e325943f6ecd0f3524e816) northd: Be more selective with installation of neighbor flows.
- [c7523f4e](https://github.com/ovn-org/ovn/commit/c7523f4e581ac93f0afd010bf09448bc89864ca6) controller: Fix mapping of learned routes to LRP.
- [32d847a0](https://github.com/ovn-org/ovn/commit/32d847a0d2ad5c1135d667d534f24e2bae908042) northd: Fix advertised route for ECMP static route.
- [154aef74](https://github.com/ovn-org/ovn/commit/154aef74e08c59478ded4bbd7916ed9dab5b856e) tests: Use localhost when setting "wrong" ovn-remote.
- [ca0067f5](https://github.com/ovn-org/ovn/commit/ca0067f5a0e9a54cfac2d6a4d2f06b97736163a6) tests: Expect musl error string for EIO errno.
- [774fae62](https://github.com/ovn-org/ovn/commit/774fae622fef55dbe0def765f154a4094ac0effc) controller: Avoid IPv6 Mac_Binding related transaction errors.
- [bee17aa0](https://github.com/ovn-org/ovn/commit/bee17aa0763d4f367700c8c4efee8384a987704b) controller: Postpone the route deletion after the dump is done.
- [e640cc91](https://github.com/ovn-org/ovn/commit/e640cc9137b5a40c24492a63121cded54f5e2976) controller: Remove unused ret field from struct ne_msg_handle_data.
- [7cab7109](https://github.com/ovn-org/ovn/commit/7cab7109d1a0cca685538554d941c44e22c15fbb) nit: tests: Remove unused arguments in send_icmp6_packet.
- [cf335b5d](https://github.com/ovn-org/ovn/commit/cf335b5df4d63ca29a1723e90ca41a4631545859) tests: Avoid code duplication by moving send_na to ovn_macros.
- [1ae8007f](https://github.com/ovn-org/ovn/commit/1ae8007f85294fa0be4065b458b226bb5633485d) treewide: Fix suboptimal hash results.
- [971a0e65](https://github.com/ovn-org/ovn/commit/971a0e65ac8597996ed79eea3f4954b1345863cc) controller: Add missing monitor conditions.
- [93a5046a](https://github.com/ovn-org/ovn/commit/93a5046ac4064f1ba73898048b9aa285d87ce3c2) ic: Fix loop disable/enable logical router.
- [801e1338](https://github.com/ovn-org/ovn/commit/801e1338dca037c1c615b35b67b43b3769426144) Prepare for 25.09.1.