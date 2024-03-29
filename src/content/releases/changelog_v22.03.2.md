+++
title = "Changelog v22.03.2"
[_build]
  list = 'never'
+++

### Changes from v22.03.1 to v22.03.2

- [e488bf31](https://github.com/ovn-org/ovn/commit/e488bf310092cce7bea62cfaf108637426cbf688) Set release date for 22.03.2.
- [5b0e8135](https://github.com/ovn-org/ovn/commit/5b0e81354028972a06c4bc83f447334f5eb8ac1d) ic: minor code improvements
- [5cefb15c](https://github.com/ovn-org/ovn/commit/5cefb15c7a9ec17e8b5f04f1728a9f57e677a199) ic: prevent advertising/learning multiple same routes
- [2a92afaa](https://github.com/ovn-org/ovn/commit/2a92afaad1b45b7edff9a45fc52fa822857d66b0) ic: lookup southbound port_binding only if needed
- [366512fb](https://github.com/ovn-org/ovn/commit/366512fb66eb78839bb9967ccbd9fc7a6d641289) ic: remove orphan ovn interconnection routes
- [d73b6417](https://github.com/ovn-org/ovn/commit/d73b64173b9cda387ffe29724992e5f0acf2742c) ovn-controller: Only set monitor conditions on available tables.
- [a82bb124](https://github.com/ovn-org/ovn/commit/a82bb124e00f3a4abaef8c5c978b411400791b9d) ovn-trace: Support connecting to SB raft followers.
- [3f745cb1](https://github.com/ovn-org/ovn/commit/3f745cb1d195dcea799651626ebeda980b2f7182) CI: Remove .cirrus.yml
- [9f324251](https://github.com/ovn-org/ovn/commit/9f32425139a3cbd8eee5e895e5548f6a2be7e7c5) northd: Add missing RBAC rules for BFD table.
- [b374438b](https://github.com/ovn-org/ovn/commit/b374438bf39e8a9abf2da9bc5a23d0d66d32df31) ovn-nbctl: Fix removal of BFD entry on route deletion
- [730dd68e](https://github.com/ovn-org/ovn/commit/730dd68eb10d4488c1822f147852118fbc49e6e4) controller: Fixed ovs/ovn(features) connection lost when running more than 120 seconds
- [cf47ef3b](https://github.com/ovn-org/ovn/commit/cf47ef3be74c5f2321eb550476633bd29bed7de3) ovs: Bump submodule to include latest fixes.
- [22837138](https://github.com/ovn-org/ovn/commit/22837138f093e7c3d4ee4c4f2f367fb19fc06398) ovn-controller: Fixed missing flows after interface deletion
- [6fbdf81c](https://github.com/ovn-org/ovn/commit/6fbdf81cee8430c98222386d00242cfa5aa0590e) ovn-controller: Fix releasing wrong vif
- [c8bd5ad4](https://github.com/ovn-org/ovn/commit/c8bd5ad45130275155bac01feb3493f2bb548f3b) tests: Fix flaky test "multi-vtep SB Chassis encap updates"
- [b47ba92d](https://github.com/ovn-org/ovn/commit/b47ba92dd33df5452c57d09e733adcee72d145b7) controller: Fix QoS for ports with undetected or too low link speed.
- [b81a6429](https://github.com/ovn-org/ovn/commit/b81a64293470bb4d61c024403a4cbeef522eb342) ovn-controller: Fix some issues with CT zone assignment.
- [1e2b0882](https://github.com/ovn-org/ovn/commit/1e2b0882117b3a50ba943edd399703daca7a2415) OVN-CI: Add test cases with monitor-all enabled.
- [91e1196d](https://github.com/ovn-org/ovn/commit/91e1196d976cda8776eeafffd9b7978bda30500e) OVN-CI: remove ddlog test cases.
- [6c415389](https://github.com/ovn-org/ovn/commit/6c415389b41a291015ab9c9eb39356676f7a88b8) Added test cases with ovn-northd parallelization enabled
- [6d00a3ec](https://github.com/ovn-org/ovn/commit/6d00a3ec49d27ad3ec3cf7850e0d97f05674c954) tests: Avoid matching on the OVS flow key contents.
- [68e01002](https://github.com/ovn-org/ovn/commit/68e0100236f1db0dfbfbd27e57495824293b7b23) ovs: Bump submodule to tip of branch-3.0 and add related test
- [54ed044f](https://github.com/ovn-org/ovn/commit/54ed044f29dfb8d74dbabda4675022ae3c9ffaa8) ci: Add missing tests after switch to parallel jobs
- [e058edcc](https://github.com/ovn-org/ovn/commit/e058edccfdc50ffaa29860025694fea174dde12e) OVN-CI: ovn unit tests run in parallel jobs.
- [ad82452b](https://github.com/ovn-org/ovn/commit/ad82452b5c89c07a3fba70ecfd39d743aebfaae5) CI-Actions: define matrix as a list
- [0abb1649](https://github.com/ovn-org/ovn/commit/0abb16497334f66469e197b067a15babcb48358c) ci: Use CFLAGS instead of OVS_CFLAGS
- [521c671f](https://github.com/ovn-org/ovn/commit/521c671faf147ea56d21ed45eb85c68820d5e139) Build tests with asan and ubsan together to reduce CI time.
- [d1466783](https://github.com/ovn-org/ovn/commit/d1466783e8a5ef5931168fd19eb74c525872dc58) ci: Add UB Sanitizer.
- [73c5886a](https://github.com/ovn-org/ovn/commit/73c5886aafc6f9f815008a4c0cacbc7331356e2b) controller: Add delay after multicast ARP packet
- [dcf50d75](https://github.com/ovn-org/ovn/commit/dcf50d75d829ab02ad22ed0598f0d4bc9ae6febc) controller: fix ipv6 prefix delegation in gw router mode
- [f87e14f0](https://github.com/ovn-org/ovn/commit/f87e14f0e81122e5b27c3b6f9f04b7af6269be96) spec: require python3-openvswitch for ovn-detrace
- [aa8c6d87](https://github.com/ovn-org/ovn/commit/aa8c6d8725581905dc1c0b2259a63cd85b04962f) northd: Use separate SNAT for already-DNATted traffic.
- [33e3be71](https://github.com/ovn-org/ovn/commit/33e3be71a62f6fc3ef15b562609dbe1bc87dc682) controller: Restore MAC and vlan for DVR scenario
- [9ab13163](https://github.com/ovn-org/ovn/commit/9ab131634868bf407228f0089998547768aa8ea3) northd: Fix multicast table full
- [130a8d39](https://github.com/ovn-org/ovn/commit/130a8d3957803c1b59e4a30a9d27d7c5440947dd) github: ovn-kubernetes: Update go, kube and libovsdb versions.
- [e520418d](https://github.com/ovn-org/ovn/commit/e520418d1763b19e8f83ea9d9d7c57f6ab7dda76) ci: ovn-kubernetes: Align CI jobs with recent ovn-kubernetes upstream.
- [8706146f](https://github.com/ovn-org/ovn/commit/8706146f45914d86889a2c446d83c61bbd124794) controller: Fix first ping from lsp to external through snat failing
- [bc8691d7](https://github.com/ovn-org/ovn/commit/bc8691d79c510cf593a1837d566e0499ccd5b11d) northd: Do not report WARN for empty requested-chassis
- [34c04168](https://github.com/ovn-org/ovn/commit/34c04168372494823809cdcc52f4a94fb2513226) Allow for setting the Next server IP in the DHCP header
- [0932c649](https://github.com/ovn-org/ovn/commit/0932c649cbe9d90b90853b9af2af5a96be9b46fb) NEWS: Fix NEWS file.
- [c2e8de38](https://github.com/ovn-org/ovn/commit/c2e8de38242cf0e21769692b6411cfc09257eac8) Revert "ovn-controller: fix a crash when deleting a port claimed when sb was ro"
- [dc1288ae](https://github.com/ovn-org/ovn/commit/dc1288aef481d0d234256b2ccd0f7d08b4234e38) ovn-controller: fix a crash when deleting a port claimed when sb was ro
- [f0a5f738](https://github.com/ovn-org/ovn/commit/f0a5f73850249060fa1f1d88c8c5130326a775da) controller: flush associated conntrack zone on PB release
- [e292e137](https://github.com/ovn-org/ovn/commit/e292e13765451a733d15075f0e949e92deeb18e2) Bump required python version to 3.6.
- [bc0ceeda](https://github.com/ovn-org/ovn/commit/bc0ceedaca8839fd15ffc2e923192b50b1e9dfec) tests: Fix tests/check_acl_log.py outputs.
- [7341c10f](https://github.com/ovn-org/ovn/commit/7341c10f88bc96aab5be9650c4fb5309d6e77589) northd: don't include disabled LSP's IP to Load Balancing
- [4bd9fbfa](https://github.com/ovn-org/ovn/commit/4bd9fbfa61d3f9ffdd1ebcb97306fd83fdd19c99) tests: Add missing reset_pcap_file() definition.
- [00fcddd0](https://github.com/ovn-org/ovn/commit/00fcddd0162ab0ceda7eb2fdaa2d98f3b5937676) Don't blindly save original dst IP and Port to avoid megaflow unwildcarding.
- [add4972e](https://github.com/ovn-org/ovn/commit/add4972e24bd48a08f5c32642b709e08cf5bbe7b) controller: fix potential segmentation violation when removing ports
- [bad4a849](https://github.com/ovn-org/ovn/commit/bad4a849227decf85b14bf8fea0e4cb8de25579b) binding.c: update ld->peers when lsp type updated
- [a407c9b9](https://github.com/ovn-org/ovn/commit/a407c9b9e924c67b72dc47c578324c577aed1a44) northd: Fix memory leak.
- [2c98163e](https://github.com/ovn-org/ovn/commit/2c98163e024f0543d84df44f9c0840ce0347e2bc) controller: throttle port claim attempts
- [3af319c8](https://github.com/ovn-org/ovn/commit/3af319c8ef5e732f4d1159ca23c276e0846b9003) Split out code to handle port binding db updates
- [b70e75f8](https://github.com/ovn-org/ovn/commit/b70e75f87117f8c8f1ae97665b745c0f31a918bf) northd: Do not relay local IP multicast (224.0.0.X).
- [4826a19f](https://github.com/ovn-org/ovn/commit/4826a19fae7a0d6f33df6e6fcd20567878acc753) extend-table: Fix table ID double allocation after OVS restart.
- [ebfbedd0](https://github.com/ovn-org/ovn/commit/ebfbedd0ceda723d5f78773c965529ee136a5720) ofctrl.c: Use bundle to avoid data plane downtime during the first flow installation.
- [9a0e90be](https://github.com/ovn-org/ovn/commit/9a0e90be73af6f9d16765286d1c1734e91bc7d8d) ofctrl.c: Include group changes to bundle.
- [4a34b878](https://github.com/ovn-org/ovn/commit/4a34b878d02464266c2b7ff2779de121b130e065) ofctrl: Support ovn-ofctrl-wait-before-clear to reduce down time during upgrade.
- [8684a942](https://github.com/ovn-org/ovn/commit/8684a9424875d97b14f518903ff8c3575ed5dd9f) ofctrl: Wakeup when entering S_UPDATE_FLOWS.
- [a325d9c3](https://github.com/ovn-org/ovn/commit/a325d9c32a8253a4475faab49c82002144b1497b) tests: Enable vif-plug tests and fix the vif-provider.
- [27fb6d44](https://github.com/ovn-org/ovn/commit/27fb6d440ec74636909d9e3a2ded06ea523cb3c3) ovn-ctl: Ensure that log/run directory have correct permission
- [a27f0777](https://github.com/ovn-org/ovn/commit/a27f077773c9638c77bb4ce32eaf168cd168ca6b) qos: add support for port minimum bandwidth guarantee
- [3554c5a6](https://github.com/ovn-org/ovn/commit/3554c5a6489a975ddc15a4d6df0fd9894cabb3ce) tests: check qos_max_rate and qos_burst are set
- [ea17a67b](https://github.com/ovn-org/ovn/commit/ea17a67b55ea4cea916f1efea8ea8a0830a8756a) controller: Fix IPv6 prefix delegation
- [dd0bdf5a](https://github.com/ovn-org/ovn/commit/dd0bdf5a5e85a953f4f63a3cc4515c4368b27bb4) system-tests: Reduce flakiness of IPv6 prefix delegation
- [ec933537](https://github.com/ovn-org/ovn/commit/ec933537f9b04b35ef4b79fb2b4743f9095da209) northd: handle virtual lport type update
- [822f78a0](https://github.com/ovn-org/ovn/commit/822f78a0ab0deaf27c0576104acacd124fbbd389) Fix compilation issue in fedora 37/rawhide.
- [16599fb2](https://github.com/ovn-org/ovn/commit/16599fb23344d86e00c7d5539a9dc77798d466a8) pinctrl: fix ovn-controller abort when service start.
- [6e5dc3ff](https://github.com/ovn-org/ovn/commit/6e5dc3fffa93e502c0f6584a6e2c71ebc7fddfd1) lflow: fix possible use-after-free in add_lb_vip_hairpin_reply_action
- [d13d1ab4](https://github.com/ovn-org/ovn/commit/d13d1ab4af6f51bfb1bccdb1cc60b7da70753509) ovn-ic: do not learn routes with link-local next-hops
- [a9f214a7](https://github.com/ovn-org/ovn/commit/a9f214a71dbc43e1627be3e55541481b3d7c61a5) ovn-nb: Properly document multicast flood config defaults.
- [6f0e30b2](https://github.com/ovn-org/ovn/commit/6f0e30b208d85030cfb6272866388d7a290c2bde) ovn-nbctl: Fix priority arg of lrp-set-gateway-chassis
- [3a1bb158](https://github.com/ovn-org/ovn/commit/3a1bb158e4ed25e4439373b46769b11003503912) northd: set svc_mon status to offline if port_binding released
- [a6bfa463](https://github.com/ovn-org/ovn/commit/a6bfa463aaa43ab76e3debac27b46edaa1e37087) ovs: Bump submodule to newer version
- [187ae17e](https://github.com/ovn-org/ovn/commit/187ae17ef1639d132cab7d0cbe546c4e39964bb0) northd: add condition for stateless nat drop flow in S_ROUTER_IN_GW_REDIRECT pipeline
- [c81559a5](https://github.com/ovn-org/ovn/commit/c81559a54e0e205ff3f53c48065d4b57b18f0061) northd.c: Add flow to skip put_nd action if ip6.src or nd.sll is 0
- [b1d6d92b](https://github.com/ovn-org/ovn/commit/b1d6d92b83c634049078fbf477436751ced5ccfc) Allow arbitrary args to be passed to called binary
- [8423d024](https://github.com/ovn-org/ovn/commit/8423d024d7a3965a722b53fe47ed7f37088c225d) tests: ovn-nbctl dump-flows -> ovn-sbctl dump-flows
- [9c29f552](https://github.com/ovn-org/ovn/commit/9c29f5523360e8f34542dcc10ff7419c5b492858) Fix memleak in ovn-nbctl when args can't be parsed
- [543c23cb](https://github.com/ovn-org/ovn/commit/543c23cb74ddc9ee23c1f2214952e76fb4cfb830) Fix pidfile_is_running when $cmd is not passed
- [6172f6a9](https://github.com/ovn-org/ovn/commit/6172f6a9bdcd430c56e9be81e42a2899b2e6876c) Lock pinctrl_mutex for pinctrl_wait
- [c45619f5](https://github.com/ovn-org/ovn/commit/c45619f5541a885554b974d18a1b088902316b1d) Ensure pid belongs to ovsdb-server in ovn-ctl
- [11800229](https://github.com/ovn-org/ovn/commit/11800229022e1445f8a8523a3ca5bb7c2e7c9a90) Handle re-used pids in pidfile_is_running
- [ef112287](https://github.com/ovn-org/ovn/commit/ef112287c6c063ff915d24cac6e5d5b5af3257a6) Prepare for 22.03.2.