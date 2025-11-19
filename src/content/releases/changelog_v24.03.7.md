+++
title = "Changelog v24.03.7"
[_build]
  list = 'never'
+++

### Changes from v24.03.6 to v24.03.7

- [15839d7c](https://github.com/ovn-org/ovn/commit/15839d7cb85c2dbdfe6e36ed9cf8efdc27ed82ca) Set release date for 24.03.7.
- [19f51071](https://github.com/ovn-org/ovn/commit/19f51071add49d30f5592e70b1048c577a3c1bd8) northd: Skip check_pkt_larger action for ARP.
- [dc8e703c](https://github.com/ovn-org/ovn/commit/dc8e703cfbfb490614ac4489d58900e010c62b6a) ovs: Update submodule to v3.3.7.
- [6a554744](https://github.com/ovn-org/ovn/commit/6a554744636ffdecd23ebde88f8cc3654bdc621d) ofctrl: Prevent duplicate desired flow references.
- [5b391454](https://github.com/ovn-org/ovn/commit/5b39145472aa0b9d9f0f59c3b81b909f25b5dceb) controller: Prevent other chassis with same encap IP.
- [b67d4499](https://github.com/ovn-org/ovn/commit/b67d4499f8dbedff169d13a3342ef9ee1f9aa322) tests: Fix command line break alignment.
- [15cf242e](https://github.com/ovn-org/ovn/commit/15cf242ec97b74ca9b86c50e023335c76a55c271) ic: Fix route learning for backward compatibility to >=23.09.
- [ad9f7cb4](https://github.com/ovn-org/ovn/commit/ad9f7cb407491d486ffe0b0e3fabe693f39accd4) expr: Use prefixes instead of single bit masks for inequality.
- [b8f04e0d](https://github.com/ovn-org/ovn/commit/b8f04e0dcc7fcbfbb59682aeada76222629a12f8) ovn-dbctl: Don't access uninitialized memory on the error path.
- [5b5a3674](https://github.com/ovn-org/ovn/commit/5b5a367451d4eaa8ac3f0633d6fcb7b6f6c6f259) tests: Add missing --wait options.
- [105c83b1](https://github.com/ovn-org/ovn/commit/105c83b1d3928ce3039165e301e9a7744f3bff8d) tests: Replace router and localnet port definitions with the helper commands.
- [23ef35ba](https://github.com/ovn-org/ovn/commit/23ef35ba958f44a1b905587f2a1f3a6cfd7d5c02) ovn-nbctl: Add two new helper commands.
- [4fa78fa1](https://github.com/ovn-org/ovn/commit/4fa78fa1f9316f23b138f58e7657030596fb0f9d) northd: Ensure unicast ARPs are forwarded properly.
- [f82b6d14](https://github.com/ovn-org/ovn/commit/f82b6d141f7988a45fcf2c2a722f0a6d0a1b02b7) system-tests: Ensure test interfaces are always deleted.
- [eadfbdd1](https://github.com/ovn-org/ovn/commit/eadfbdd156a37a01ed9d8364b30721c117db2443) system-tests: Remove unused common system macros.
- [c7981d68](https://github.com/ovn-org/ovn/commit/c7981d683e17a7ef33d33f2e3fbfbc123e4ac59a) controller: Don't use the split buf action.
- [25c56851](https://github.com/ovn-org/ovn/commit/25c5685164fd632ad0342dd0a484c9f7b8d9ae2c) tests: Simplify "MAC binding aging - probing GW router Dynamic Neigh"
- [76e26ba1](https://github.com/ovn-org/ovn/commit/76e26ba1f5f38e5278b5f7502d8724a710089e38) controller: Unable to allocate meter id.
- [974e5163](https://github.com/ovn-org/ovn/commit/974e51638900a2769f4ba5e119a7bcfe11bbe21c) ci: Increase the multinode test timeout.
- [2b5e2c78](https://github.com/ovn-org/ovn/commit/2b5e2c787bbc9e3a2e965b03e368a5e443d11727) northd: Fix receiving NA on non resident chassis.
- [2d516d9f](https://github.com/ovn-org/ovn/commit/2d516d9f43c0f3152a21304debdca09aa98bf096) tests: Also remove patch ports when cleaning up resources.
- [2318e8f1](https://github.com/ovn-org/ovn/commit/2318e8f111bff69768ccc2c145d52ef196b63053) controller: Do not assign pointer to bool.
- [cfdd380a](https://github.com/ovn-org/ovn/commit/cfdd380a025edbfd947c07844684fb6f7ab81c63) northd: Prevent ovn-nbctl --wait=sb from returning early.
- [532f857e](https://github.com/ovn-org/ovn/commit/532f857e2ebda0fc5af21d1647e7036d27f38447) northd: Be more selective with installation of neighbor flows.
- [f27dfe15](https://github.com/ovn-org/ovn/commit/f27dfe1539eb00d1dca2fefa7d4cd5e313064dec) tests: Use localhost when setting "wrong" ovn-remote.
- [62f62f01](https://github.com/ovn-org/ovn/commit/62f62f0195fb1b519276580cfcd1d25caf269824) tests: Expect musl error string for EIO errno.
- [93be64d9](https://github.com/ovn-org/ovn/commit/93be64d9e95f1c7c8a0ee82292cc7078772df270) controller: Avoid IPv6 Mac_Binding related transaction errors.
- [76d7402a](https://github.com/ovn-org/ovn/commit/76d7402ab418480c8ddd968b868bb44f8def451d) nit: tests: Remove unused arguments in send_icmp6_packet.
- [381ed905](https://github.com/ovn-org/ovn/commit/381ed90502eabae3833c4ad8dccb8ffb473e7932) tests: Avoid code duplication by moving send_na to ovn_macros.
- [363c1b36](https://github.com/ovn-org/ovn/commit/363c1b36cadb5c8c45fb4a644342cc831d8cdb79) controller: Add missing monitor conditions.
- [0e1cfa6a](https://github.com/ovn-org/ovn/commit/0e1cfa6a330737f8719b470d2ec8e35302c4294a) ic: Fix loop disable/enable logical router.
- [32a59f1d](https://github.com/ovn-org/ovn/commit/32a59f1d7a682c04d30916c7bef3286ecbd7e1f3) ovn-sandbox: Fix typo that doesn't allow starting a sandbox without IC.
- [de4a70eb](https://github.com/ovn-org/ovn/commit/de4a70eb356342a3d4e37588652b4f0af7ca9eff) northd: Always prefer bound ovn_port versions when available.
- [b2c8f560](https://github.com/ovn-org/ovn/commit/b2c8f560cb73821151b3ef3d090f93dac2a01865) northd: Omit alert for write-only SB.Static_Mac_Binding table.
- [1544c04d](https://github.com/ovn-org/ovn/commit/1544c04d109bec443b75da89f72952d43a0be5d3) mac-cache: Handle never hit flows correctly.
- [be2ee65a](https://github.com/ovn-org/ovn/commit/be2ee65ac17a4b7fd8c227f887ec05ccf8d4ac5a) northd: Update the SB datapath reference for Static MAC binding.
- [5771eb51](https://github.com/ovn-org/ovn/commit/5771eb5181b7f39f89f372caa610bea454b479be) multinode: Check proper GARP generation.
- [37992e62](https://github.com/ovn-org/ovn/commit/37992e62f56f7197700c9fcbaef866af51525630) controller: Fix missing garp while gw are fighting.
- [20ce2103](https://github.com/ovn-org/ovn/commit/20ce2103679a14bc79693fcf077a78bd9d5c585e) controller: Do not postpone claim for highest priority chassis.
- [32a74b79](https://github.com/ovn-org/ovn/commit/32a74b79237ecbd5dc71f75d3f97d4bad9c6ad49) multinode: Fix backport of multinode tests.
- [64ca4fdf](https://github.com/ovn-org/ovn/commit/64ca4fdf72cb486fa38f21efe910fd5e787ed689) northd: Remove stale Static MAC Bindings during SB datapath re-creation.
- [584eae5e](https://github.com/ovn-org/ovn/commit/584eae5e12fdca6affb562ad5b8b6cd5ae2a5a09) tests: Fix flaky "pod to pod with localnet_learn_fdb".
- [8495cb95](https://github.com/ovn-org/ovn/commit/8495cb9528d60b3cb25fcaead0eb9a41891eaa2a) controller: Fix potentially missing vif entries in fdb.
- [1f490457](https://github.com/ovn-org/ovn/commit/1f49045771adb9706ba2397448447a5ae784ed33) controller: Update next_cfg when transaction succeeded.
- [a87fc827](https://github.com/ovn-org/ovn/commit/a87fc827380efe3617b7de3470a3f76724f62aea) northd: Update virtual port on parent port update.
- [d162828a](https://github.com/ovn-org/ovn/commit/d162828a38e343f047252f036e5cb237835b4294) logical-fields: Fix IPv6 dp flow explosion caused by ip6.mcast_rsvd.
- [eece7128](https://github.com/ovn-org/ovn/commit/eece7128ceede01eddf70cbe068ee5a868de5565) ovn-trace: Fix pop action in trace.
- [37f0b273](https://github.com/ovn-org/ovn/commit/37f0b273e88cead94ad2aef74e5613b8cf13297d) tests: Fix flaky "interconnection".
- [51dab692](https://github.com/ovn-org/ovn/commit/51dab692386514eee2f94aceb05dd79b534b05e6) tests: Add missing check for scapy.
- [a5bb17b6](https://github.com/ovn-org/ovn/commit/a5bb17b6b93fddbffeb8a9a0a480966a34d9e971) tests: Remove unused commands from mac-binding test.
- [308e6e88](https://github.com/ovn-org/ovn/commit/308e6e882eee0cd5b22b3d3d434d2b6a822a7a3e) tests: Fix flaky "send arp for nexthop".
- [7e967334](https://github.com/ovn-org/ovn/commit/7e9673344602033ce763c81694c3af1aa92b6fc7) tests: Fix flaky tests not properly waiting for ovn-controller exit.
- [e0e2c81d](https://github.com/ovn-org/ovn/commit/e0e2c81d05530c56653816122d9b2b9366c32883) tests: Fix flaky "NAT on a provider network with no localnet ports".
- [df1c28bb](https://github.com/ovn-org/ovn/commit/df1c28bbccf0c8dc4da0f34e79c18064a466925a) tests: Avoid calling ovs/ovn commands when ovs/ovn are stopped.
- [20c7b13c](https://github.com/ovn-org/ovn/commit/20c7b13c5f3cafc7e583fd1d07d91323f274c14e) tests: Avoid unloading not existing modules.
- [50d4b467](https://github.com/ovn-org/ovn/commit/50d4b467cb10ef0a84d64c09533518d44498b26a) ovn-nbctl: Fix lrp set gateway chassis duplicate gc.
- [20a9681e](https://github.com/ovn-org/ovn/commit/20a9681e13ccd16879d54dae4fc91021be37266d) multinode.at: Cleanup test interfaces created in br-ex.
- [5034c5ac](https://github.com/ovn-org/ovn/commit/5034c5acc938d06d916315df420a11e8c43750be) ovn-ctl: Fix ovsdb-server/sync-status command output.
- [32e867b3](https://github.com/ovn-org/ovn/commit/32e867b33a5a83bcd0b1e029f58bc2c0e41bbeac) controller: Slightly optimize the runtime_data handler for sb_ro.
- [39bcc82d](https://github.com/ovn-org/ovn/commit/39bcc82d5e12d3b00038a29775ee081a6cc4be38) Revert "northd: Don't skip the unSNAT stage for traffic towards VIPs."
- [fa72c3fc](https://github.com/ovn-org/ovn/commit/fa72c3fccefbbddd473a07b8c23b5927ae9522f9) test: Add missing sync calls.
- [ab9e8802](https://github.com/ovn-org/ovn/commit/ab9e88029de6a14e29f7764b4099bc12449e80c1) controller: Install QoS rules even on 'system' ports.
- [af8e1b4a](https://github.com/ovn-org/ovn/commit/af8e1b4a982b4cdec2184ff60845b045b3e92023) controller: Make sure we run engine_cleanup after thread destroy.
- [cdad4e7e](https://github.com/ovn-org/ovn/commit/cdad4e7e00b02169ce4ab268cde2e160faeae68a) Prepare for 24.03.7.