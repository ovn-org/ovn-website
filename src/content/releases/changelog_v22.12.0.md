+++
title = "Changelog v22.12.0"
[_build]
  list = 'never'
+++

### Changes from 22.09.0 to v22.12.0

- [2a081933](https://github.com/ovn-org/ovn/commit/2a081933affc62dc2b985e914708d01ee10a7f79) Set release date for 22.12.0.
- [de16bcba](https://github.com/ovn-org/ovn/commit/de16bcbaac8e37a4fe4609e538759be8462307de) ic-sb schema: add index for routes table & document upgrade path
- [f61f87bd](https://github.com/ovn-org/ovn/commit/f61f87bdf79f9f5535f49ce24e40e450f9d2ea03) ic: minor code improvements
- [969f41dc](https://github.com/ovn-org/ovn/commit/969f41dc9fb43e2b23abfa4655d07372ed3016fa) ic: prevent advertising/learning multiple same routes
- [d7b109f1](https://github.com/ovn-org/ovn/commit/d7b109f146d0e30ded46742d02747723c9f929e7) ic: lookup southbound port_binding only if needed
- [ff3ba025](https://github.com/ovn-org/ovn/commit/ff3ba025974b20bb32bc37f140f0fa9fa9feb228) ic: remove orphan ovn interconnection routes
- [7a29dfc4](https://github.com/ovn-org/ovn/commit/7a29dfc48c209b5b654d20f569e7e69309bc41a3) northd: Store skip_snat and force_snat in ct_label/mark
- [87d46623](https://github.com/ovn-org/ovn/commit/87d4662383f298e4e96363fd68e8335c3598b86a) northd: Add logical flow to defrag ICMP traffic
- [428bcde4](https://github.com/ovn-org/ovn/commit/428bcde4c340539cbd2da15512ba7dac3c62cce6) AUTHORS: Add Abhiram R N  and Veda Barrenkala.
- [323f978c](https://github.com/ovn-org/ovn/commit/323f978cbf4599568fcca9edec8ed53c076d2664) OVN Remote Port Mirroring: controller changes to create ovs mirrors
- [b9a073b7](https://github.com/ovn-org/ovn/commit/b9a073b7a9b6d31cc330d8410ec34bbb409fd071) OVN Remote Port Mirroring: northd changes to sync NB and SB
- [c0190fdd](https://github.com/ovn-org/ovn/commit/c0190fdd5196c690519513b5d1fb1cafa2bfee22) OVN Remote Port Mirroring: Add new Schemas in NB
- [3a71d4cc](https://github.com/ovn-org/ovn/commit/3a71d4cce6b4f3c9b2d12b0eaaa89f185ed92662) ovn-controller: Only set monitor conditions on available tables.
- [4777e5c8](https://github.com/ovn-org/ovn/commit/4777e5c8ddcfb492b45014e071ad5ea188300015) ovn-trace: Support connecting to SB raft followers.
- [85f57c87](https://github.com/ovn-org/ovn/commit/85f57c872117afa15846ebaa1f7fa0fc80006c26) CI: Remove .cirrus.yml
- [4e262889](https://github.com/ovn-org/ovn/commit/4e262889cfba5424337b25b266cbdb3ea7fade1c) controller: Check if MAC binding table has timestamp column
- [7c5412de](https://github.com/ovn-org/ovn/commit/7c5412deb5c38db025c8160ffcb1fc065074f083) northd: Add missing RBAC rules for BFD table.
- [5d906a04](https://github.com/ovn-org/ovn/commit/5d906a043c8a68776d2fac70da8457c5826e7ecb) ovn-nbctl: Fix removal of BFD entry on route deletion
- [62652fda](https://github.com/ovn-org/ovn/commit/62652fdab88dff9de483411629a8d824a4f034c7) northd: Include VIP port in LB affinity learn flow matches.
- [09c91db5](https://github.com/ovn-org/ovn/commit/09c91db57c50a149a2678aca7c8e8a67c8fc5e9b) tutorial: Add scripts to simulate node-port ovn-k8s services.
- [589b13e0](https://github.com/ovn-org/ovn/commit/589b13e0865421038cbe303da047b81c0e6eb086) lb: Support using templates.
- [78e3022a](https://github.com/ovn-org/ovn/commit/78e3022aca4d802eb6da6813e88a954772aba932) controller: Add support for templated actions and matches.
- [cb2e3113](https://github.com/ovn-org/ovn/commit/cb2e3113f0f697eb4863dd817bff6424bbfe0721) Add NB and SB Chassis_Template_Var tables.
- [e63f9216](https://github.com/ovn-org/ovn/commit/e63f921604f5dbb900cb538d71a7edb589538597) lflow: Factor out the lflow reference handling code into a new module.
- [8e315b85](https://github.com/ovn-org/ovn/commit/8e315b85ba7a5ed7cae114f327792bc536c81a88) northd: Improve the LB affinity code
- [14219f49](https://github.com/ovn-org/ovn/commit/14219f492a1c4752767faa21686cda6e0b71969e) Prepare for 22.12.0.
- [650f06b9](https://github.com/ovn-org/ovn/commit/650f06b9f3e2b2f16df9bd9fd4987c702bde4956) northd: Allow related traffic through LB
- [31196346](https://github.com/ovn-org/ovn/commit/31196346fcad9aaa30fc242a8a58db1396225d50) actions: Add new action called ct_commit_nat
- [94fef2df](https://github.com/ovn-org/ovn/commit/94fef2df7bc76a9a99eb85ee3737cb396d66bdf5) tests: change recompute test case (reduce time)
- [36ae3e1e](https://github.com/ovn-org/ovn/commit/36ae3e1e3b12478cab13cb5b6fe6e9f89b9b096a) CI: Update GH actions version
- [280ac8cd](https://github.com/ovn-org/ovn/commit/280ac8cdd579007bf8e661ad2b67322ed9757298) NEWS: Mention the new load balancer affinity_timeout option.
- [981ffce4](https://github.com/ovn-org/ovn/commit/981ffce438e426bee005ddff676c236c96af8004) ovn-util: Bump OVN internal minor version for new stages.
- [ff001428](https://github.com/ovn-org/ovn/commit/ff00142808dc49a33baccf3e11bb0b3fe3385444) controller: Fixed ovs/ovn(features) connection lost when running more than 120 seconds
- [c61a0e1d](https://github.com/ovn-org/ovn/commit/c61a0e1d03da93ed47daf31892e9b0f69982efee) ci: github: Enable address and UB sanitizers for system tests.
- [a42c808f](https://github.com/ovn-org/ovn/commit/a42c808f30b40f318c85295738df76718d0b94d0) northd: add drop sampling
- [27a92cc2](https://github.com/ovn-org/ovn/commit/27a92cc272aa55a1b97d7f542564f11a204d4ed3) northd: make default drops explicit
- [0b13d296](https://github.com/ovn-org/ovn/commit/0b13d29687439c29da275163fed767cb333341dd) actions: add sample action
- [52cb9c3b](https://github.com/ovn-org/ovn/commit/52cb9c3b41c24556d4ec95d1c381ab47b73c0898) ovn-controller: Fixed missing flows after interface deletion
- [a2f80ce2](https://github.com/ovn-org/ovn/commit/a2f80ce2436306bf4938ef7c7925ece3d6cd3e20) ovn-controller: Fix releasing wrong vif
- [0d5e0a6c](https://github.com/ovn-org/ovn/commit/0d5e0a6ced49f4cf059701bcfc29dd595c087c73) northd: Add I-P for syncing SB address sets.
- [ccafcc2d](https://github.com/ovn-org/ovn/commit/ccafcc2dc321b38e4b026abc6d2f4d6951f7321e) northd I-P: Add a new engine node 'en_sync_to_sb' to sync SB tables.
- [757193ef](https://github.com/ovn-org/ovn/commit/757193efd857ba5ce7043c93ced61b19fc00c665) Enhance the unixctl command inc-engine/show-stats
- [29bd0c6b](https://github.com/ovn-org/ovn/commit/29bd0c6b0a644564688213b314f531d04b76123e) tests: Fix flaky test "multi-vtep SB Chassis encap updates"
- [f6edbc02](https://github.com/ovn-org/ovn/commit/f6edbc02929583e0d66ee7938264b471c7cda397) tests: Fix flaky test "IPv6 Neighbor Solicitation for unknown MAC"
- [91d063ed](https://github.com/ovn-org/ovn/commit/91d063edf70f214dd0bd0c884e090deabb7b07cc) Don't test python3.4, python3.5 binaries in OVN_CHECK_PYTHON3 m4 check.
- [d3926b43](https://github.com/ovn-org/ovn/commit/d3926b433e446ee95ae3b7c02569818eaea5e24d) northd: rely on new actions for lb affinity
- [0df2dc78](https://github.com/ovn-org/ovn/commit/0df2dc7884d07812675cf4ae225f15d60d5c784e) actions: introduce chk_lb_aff action
- [216201a2](https://github.com/ovn-org/ovn/commit/216201a2b5d6ef00b462f2fb014477ccca58bc76) actions: introduce commit_lb_aff action
- [661094c4](https://github.com/ovn-org/ovn/commit/661094c40e6c7ef67778e0229a8861d33bb63bf5) controller: Fix QoS for ports with undetected or too low link speed.
- [a042aa23](https://github.com/ovn-org/ovn/commit/a042aa23e79a0d36f1ce7b0ccfcf0a5995b045cd) pinctrl: Use 16-aligned 32-bit fields in bfd_msg.
- [0d556ed9](https://github.com/ovn-org/ovn/commit/0d556ed9e0283e7b0ec2ba05e79a1314da2c6360) ovs: Bump submodule to include latest fixes.
- [554e334f](https://github.com/ovn-org/ovn/commit/554e334f753f16c367273bdb33e0b2435b31c0b1) ovn-controller: Fix some issues with CT zone assignment.
- [9ac54852](https://github.com/ovn-org/ovn/commit/9ac5485242183fcfc0ecaed5c1c15a6ba68c420f) pinctrl: Send RARPs for external ipv6 interfaces
- [1c6167d2](https://github.com/ovn-org/ovn/commit/1c6167d2b9b61cbe409cc92505da2e832f9fe0bc) ovn-macros: support ipv6 in ovn_attach
- [666c8e0c](https://github.com/ovn-org/ovn/commit/666c8e0cb12f1418f05b05cdc3a8a55a7b4b4db4) northd: handle own rarps like garps
- [3531c18f](https://github.com/ovn-org/ovn/commit/3531c18f54461efddcf7cbd24e4d8b289d135ff0) logical-fields: add rarp fields
- [03449fa7](https://github.com/ovn-org/ovn/commit/03449fa72baf7e1a824bf2660d3d1675f03217de) ci: Update jobs to use numbers instead of test flags
- [40df933c](https://github.com/ovn-org/ovn/commit/40df933ce49946c69099a902b154d7bfee4358a3) northd: add the capability to inherit logical routers lbs groups on logical switches
- [b8875fdb](https://github.com/ovn-org/ovn/commit/b8875fdbaf747608faf3474be0b6717da681232f) ovn-northd-ddlog: Remove custom uuidset implementation.
- [6a698374](https://github.com/ovn-org/ovn/commit/6a6983747c3f04b6ab0df6347f39f6e70eab978b) AUTHORS: Add Jun Gu.
- [85ffa225](https://github.com/ovn-org/ovn/commit/85ffa22505d568124c0bafa1054c79cf7370d7a2) ovn: Remove SBREC_TABLE_HA_CHASSIS ctl_table
- [49f1d71f](https://github.com/ovn-org/ovn/commit/49f1d71f091d58c6a4622ce0f1ed219453f59a74) util: Avoid double parsing of LB vip and backend ip
- [ed03a8da](https://github.com/ovn-org/ovn/commit/ed03a8dabf1b3d691d589e00a4595e9de46d855b) tests: Don't run ovn-northd specific tests with ovn-controller flavors.
- [6d4a5500](https://github.com/ovn-org/ovn/commit/6d4a5500ea752efa7a9da03259f0c2fa777dca6e) controller: Remove unused shash from update_ct_zone
- [f83263c2](https://github.com/ovn-org/ovn/commit/f83263c2d5544347c71cdf48fb62ded299a302b8) controller: fix ipv6 prefix delegation in gw router mode
- [00de1d75](https://github.com/ovn-org/ovn/commit/00de1d75513f911489b5b4c9afcecaebe7e05e7a) northd.c: Adjust and add stopwatch for "lflows_to_sb".
- [58861071](https://github.com/ovn-org/ovn/commit/5886107159e86bc1f8b9e16834efbe3bcf497a13) spec: require python3-openvswitch for ovn-detrace
- [ea2e5b33](https://github.com/ovn-org/ovn/commit/ea2e5b3303c3a89189055f723777f7fff3ad9f1f) lflow: Use uuidset instead of lflow_processed_node maps.
- [51daeff8](https://github.com/ovn-org/ovn/commit/51daeff850f5a5323423a3118961a03dc348c780) ofctrl: Use uuidset instead of ofctrl_flood_remove_node maps.
- [1281864f](https://github.com/ovn-org/ovn/commit/1281864f4d8faa6cf0938d4c38250353b6136f1f) checkpatch.py: Port checkpatch related changes from the OVS repo.
- [c0addf8e](https://github.com/ovn-org/ovn/commit/c0addf8e0a36432ffa1e742761aa1e2216d9f109) tests: Use grep -E and grep -F instead of obsolete egrep/fgrep.
- [821df08d](https://github.com/ovn-org/ovn/commit/821df08dd5619f6a7fc16fa3ff52c687c983ea01) northd: Use separate SNAT for already-DNATted traffic.
- [54b63520](https://github.com/ovn-org/ovn/commit/54b635204dfdf6020c297203bfc2d1cebab14769) northd: do not centralize FIP traffic if redirect-type is set to fixed
- [ef739fb8](https://github.com/ovn-org/ovn/commit/ef739fb8a710158fd0ea3d5253cfef79d1af8bd6) controller: Avoid building dhcp/nd_ra/controller_event opt maps every time.
- [36a70731](https://github.com/ovn-org/ovn/commit/36a70731585a62490479a25ab9f1aa85ba7c05e3) controller: Restore MAC and vlan for DVR scenario
- [a0d40589](https://github.com/ovn-org/ovn/commit/a0d40589c518b8059e24b815f4a98e910ebfa09d) northd: Fix multicast table full
- [2e4f3936](https://github.com/ovn-org/ovn/commit/2e4f393650ccf298f26787583c13a88197ba8348) ovs: Bump submodule to newer version and add related test
- [f12ae168](https://github.com/ovn-org/ovn/commit/f12ae16814a8081da31e4eb731028b2132d2762d) controller: Fix first ping from lsp to external through snat failing
- [70eb0aba](https://github.com/ovn-org/ovn/commit/70eb0aba6439805a7d00502c708fcc636c37da7f) treewide: Fix various typos in manual pages
- [1034ba76](https://github.com/ovn-org/ovn/commit/1034ba7616d4873ed9923065f1e24ca05f3c8dd2) controller: Remove unnecessary IDL table casts.
- [fea2a7b6](https://github.com/ovn-org/ovn/commit/fea2a7b6e2d6da8d9cb712b32c28bcc183c4e830) doc, ovn-nbctl: Make it clear that LB can be without protocol
- [629e9309](https://github.com/ovn-org/ovn/commit/629e9309df7fa1305eab23a313ab90b9efc5c82e) ovn-controller: Track OVSDB column open_vswitch:external_ids.
- [182dd332](https://github.com/ovn-org/ovn/commit/182dd3321030520210d186a5f61da6990abd6ebd) ovn-controller: Adjust the order of monitor/track columns.
- [140193bd](https://github.com/ovn-org/ovn/commit/140193bd43c113e6339b30af068c6a4ebcee1f21) ovn-nbctl: Simplify load balancer related code.
- [a35a661b](https://github.com/ovn-org/ovn/commit/a35a661bb29a113fdc64134a641527f8a59c3a36) pinctrl fix missing packets (e.g. icmp)
- [bfa832c7](https://github.com/ovn-org/ovn/commit/bfa832c719b590674c64071d6712447537423d40) MAINTAINERS: Add Dumitru Ceara.
- [d91018e0](https://github.com/ovn-org/ovn/commit/d91018e06f2068c8676dfc5bb6dc6d505ef20314) tests: fix multiple flaky test cases
- [466ec1a8](https://github.com/ovn-org/ovn/commit/466ec1a86e36f7dec247eb68216ff71ba8ba4ab3) lb: Remove unused ovn_northd_lb_vip vip_port_str member.
- [27b7c102](https://github.com/ovn-org/ovn/commit/27b7c102ce3e3a1f948ef6928b09f82bb9a82cb7) Set release date for 22.09.0.
- [ca27c41e](https://github.com/ovn-org/ovn/commit/ca27c41ea7ac32caddc3e7e0c5de67925cb03ce3) northd: Use bitmaps instead of exclusive hash map for datapath groups.
- [8b04fa92](https://github.com/ovn-org/ovn/commit/8b04fa9293f73d0e98d883f630d50ced75d416ef) ovn-controller: fix a crash when deleting a port claimed when sb was ro
- [91934ad7](https://github.com/ovn-org/ovn/commit/91934ad7c3a6599574cee16b3a23ac97d95c65fb) northd: drop traffic to disabled LSPs in ingress pipeline
- [f386a029](https://github.com/ovn-org/ovn/commit/f386a02976ed526baf160dd3129b0d431c73a807) controller: flush associated conntrack zone on PB release
- [6cbda808](https://github.com/ovn-org/ovn/commit/6cbda808a2dc1f5beda39cbe50451f8d834d609a) Bump required python version to 3.6.
- [ebd6bdd3](https://github.com/ovn-org/ovn/commit/ebd6bdd3e34301574c8c5f427d6682c1131915df) tests: Fix tests/check_acl_log.py outputs.
- [ae456e4f](https://github.com/ovn-org/ovn/commit/ae456e4fb70175ba8ec6bee96102bf9d85af3853) northd: Don't get stuck in the STATE_INIT_HASH_SIZES state.
- [a88e769e](https://github.com/ovn-org/ovn/commit/a88e769e43f54fa6b12f92faca30dfb55eb1f323) northd: don't include disabled LSP's IP to Load Balancing
- [59c78a6a](https://github.com/ovn-org/ovn/commit/59c78a6a61b20deb105dd3c1e017c392cce4036b) northd: Re-use IP sets created for load balancer groups.
- [f78f14d9](https://github.com/ovn-org/ovn/commit/f78f14d92feadd27276bada5f711d217687af132) northd: Retrieve load balancer options only once.
- [ddff34f6](https://github.com/ovn-org/ovn/commit/ddff34f63eb56b03f56439e328c14d14eaee9ab4) northd: Add datapaths to load balancers in bulk.
- [2fd2833e](https://github.com/ovn-org/ovn/commit/2fd2833eccb22e0630280536bf495ef62f60d4cb) northd: Optimize load balancer lookups for groups.
- [703949bd](https://github.com/ovn-org/ovn/commit/703949bd8b9a5d1c8928ab6199c27ea689350874) northd: Accumulate more database updates before processing.
- [54b71e44](https://github.com/ovn-org/ovn/commit/54b71e4465e6a7769f819702abca6e864f6751ed) northd: Properly check the wakeup time in MAC banding aging
- [1139b655](https://github.com/ovn-org/ovn/commit/1139b655c996e520762dd3e7e43a9bd87b12be75) Don't blindly save original dst IP and Port to avoid megaflow unwildcarding.
- [9dac6b7d](https://github.com/ovn-org/ovn/commit/9dac6b7dee3d7927123674aadb7a580684f11793) northd: don't add drop lflow if LB VIP matches LRP IP