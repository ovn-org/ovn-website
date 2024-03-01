+++
title = "Changelog v23.09.1"
[_build]
  list = 'never'
+++

### Changes from v23.09.0 to v23.09.1

- [0afd4e59](https://github.com/ovn-org/ovn/commit/0afd4e59e95b5f8c7b56760e91269786b0e0e52a) Set release date for 23.09.1.
- [7fd87c5d](https://github.com/ovn-org/ovn/commit/7fd87c5d0b1492c14d90faec4af4069496ae3609) northd: Add missing stopwatch initialization.
- [b2f83984](https://github.com/ovn-org/ovn/commit/b2f839849c36c058f940c417dc29e26165a1d30e) controller: avoid extra flows if localnet_learn_fdb is disabled
- [33b01175](https://github.com/ovn-org/ovn/commit/33b0117598b23b8c0877e482ee350283a147bb5f) controller: FDB entries for localnet should not overwrite entries for vifs
- [bbd07439](https://github.com/ovn-org/ovn/commit/bbd07439b9a8cd6db901bffcac7ac17f58e33a07) controller: Disable inactivity probe for statctrl
- [617b84d7](https://github.com/ovn-org/ovn/commit/617b84d7dd2ce3501b49e988e1ba06e86889c9bd) pinctrl: reset success and failures n_count regardless of svc state
- [beb26027](https://github.com/ovn-org/ovn/commit/beb26027cf26271c7cd780869b540737c7916e99) pinctrl: send RST instead of RST_ACK bit for lb hc
- [e9e716ad](https://github.com/ovn-org/ovn/commit/e9e716ad531e34766d2f02783ac08955096bf636) controller: Don't artificially limit group and meter IDs to 16bit.
- [d257d800](https://github.com/ovn-org/ovn/commit/d257d800e41388bd2a387e0b6d5a0e41c2e8d8f1) tests: fixed race_condition with max_prefix
- [dab54b81](https://github.com/ovn-org/ovn/commit/dab54b81c7ee767943163f2aaaa27b2c4b367964) tests: have CHECK_NO_CHANGE_AFTER_RECOMPUTE potentially wait for ports up
- [d2e0acb2](https://github.com/ovn-org/ovn/commit/d2e0acb2a6aa510282da5e04036ec5258454c351) tests: fixed "ovn-nbctl - daemon retry connection"
- [0bb6ba90](https://github.com/ovn-org/ovn/commit/0bb6ba908421825428ec904d5316ae13090adbbf) tests: fixed system test "LR with SNAT fragmentation needed for external server".
- [810d83e7](https://github.com/ovn-org/ovn/commit/810d83e77ce3398bc94469404d85a01eb63e40bd) tests: fixed "interconnection - static multicast" and "- IGMP/MLD multicast"
- [25d4b685](https://github.com/ovn-org/ovn/commit/25d4b6855f6ce3795314e9439716f775994c7f4d) ovn-ctl man: Add election timer config to manpage
- [5375cdd9](https://github.com/ovn-org/ovn/commit/5375cdd96eaf8e527e5afea402f279990398710c) Fix flows not removed in ha migration
- [619abe5c](https://github.com/ovn-org/ovn/commit/619abe5c5e18f417fe20b252ca41b70e644466e0) binding: handle pb->chassis and pb->up from if-status module
- [d039b433](https://github.com/ovn-org/ovn/commit/d039b4332b9ea739bdf6b2efc9f5f3e422fe9a42) binding: slight refactor if no local binding in consider_iface_release
- [f5d01be7](https://github.com/ovn-org/ovn/commit/f5d01be7f1337bdc7885dd45592aa3b376467790) controller: have I+P assigning ct_zones for l3gateway ports
- [650bffdb](https://github.com/ovn-org/ovn/commit/650bffdbe0562dc364faaef51f51f99e82cccc56) tests: fixed another set of flaky ovn-ic tests
- [b3d03b94](https://github.com/ovn-org/ovn/commit/b3d03b94178bee2479d6f66ffa34255a7feb79eb) tests: wait for all flows to be installed before sending packets
- [ac3ece28](https://github.com/ovn-org/ovn/commit/ac3ece28ca04cb74b21c80e2bd73767e29cca9a3) tests: fixed "ipsec -- basic configuration"
- [fcbc0ae1](https://github.com/ovn-org/ovn/commit/fcbc0ae1c66e31c38ad9d5e099237e7446958035) tests: fixed "LSP incremental processing"
- [54fae8cb](https://github.com/ovn-org/ovn/commit/54fae8cbb5db827da95a2a52ff28f29e6c7740fe) tests: do not start backup-northd by default
- [a1422144](https://github.com/ovn-org/ovn/commit/a1422144228bb9924dbc75782734a09c6ecfa534) tests: fixed multiple tests not properly waiting for packets to be received
- [627955eb](https://github.com/ovn-org/ovn/commit/627955eb79c2cd374853319c1d271c2fd1aeac37) ci: Pin Python, Fedora and Ubuntu runner versions.
- [1fa7628d](https://github.com/ovn-org/ovn/commit/1fa7628db4155d3a39d55fe61d8d19fa7d3030af) ovs: Bump submodule to include E721 fixes.
- [5044376d](https://github.com/ovn-org/ovn/commit/5044376da0a1c14d1ccc4b41dfdbae14e74746b2) tests: Remove broken "feature inactivity probe" test.
- [84c93511](https://github.com/ovn-org/ovn/commit/84c93511ce9a612b9a815cc1403b4841cc2e4c58) readthedocs: Add the configuration file.
- [39236dc3](https://github.com/ovn-org/ovn/commit/39236dc3151baa3ace58c3ecd62ba0384b4c7a05) Documentation: Use theme from Read The Docs.
- [74172ed4](https://github.com/ovn-org/ovn/commit/74172ed481f7c239d9258845eb493f17d731df99) ovs: Bump submodule to v3.2.1.
- [c6a631f0](https://github.com/ovn-org/ovn/commit/c6a631f066eea105c57c265dc68257d1b5ee18e4) py-requirements: Remove hacking dependency and use recent flake8.
- [be4364e6](https://github.com/ovn-org/ovn/commit/be4364e62ac739744c1ef5bdd74a85fe39d6e37d) ovn-ic: wakeup on ovsdb transaction failures
- [5f84ff65](https://github.com/ovn-org/ovn/commit/5f84ff658bfd1c26bd9749c3d2e09a7e3567a8bd) ovn-ic: fix potential segmentation violation when ts is deleted
- [aae5b2ec](https://github.com/ovn-org/ovn/commit/aae5b2ec8ec9f4f9f7c9738d23818c2c4967627c) controller, northd: Wait for cleanup before replying to exit
- [ea9310a5](https://github.com/ovn-org/ovn/commit/ea9310a5f1e37b373abffd85f7a8dd4fefc30c4e) tests: Add missing check for scapy.
- [15bf24b8](https://github.com/ovn-org/ovn/commit/15bf24b889b178d4cdbb6166d3bc5434ec59f9fc) ci: Apply the ASAN workaround only for Clang <16
- [2efc23f3](https://github.com/ovn-org/ovn/commit/2efc23f3edf0293ec81a167e1c4bf99fe5601ca2) ci: Use proper uname argument to get the HW type
- [349266aa](https://github.com/ovn-org/ovn/commit/349266aac20f229b10ef0313c9f4e6b5f1af4ede) tests: Wait for new ovn-controllers to connect to Southbound.
- [df7656fb](https://github.com/ovn-org/ovn/commit/df7656fbf6a4ec1175b8f464a1aa6ed6e74fde29) northd: Reset ls_datapath_group if not all chassis support it.
- [276b9d47](https://github.com/ovn-org/ovn/commit/276b9d47183ebd31c382742025e562fda8d14d11) northd: introduce ls_datapath_group column in lb sb db table
- [c33398e3](https://github.com/ovn-org/ovn/commit/c33398e32b2753dd6c0cecf35ba48ad8faa69bfc) northd: sync lb applied to logical routers in sb db lb table
- [e8c79cec](https://github.com/ovn-org/ovn/commit/e8c79cecef9d6e15673be1a604baaaca083f0016) northd: Avoid snat on reply packets for dgw
- [a9788ef3](https://github.com/ovn-org/ovn/commit/a9788ef39e003b04ec426761833d85bbec1f3b84) northd: Incrementally process SB.Load_balancer updates.
- [cadfefdf](https://github.com/ovn-org/ovn/commit/cadfefdf1c6457d25b6d1f93e217493739418365) tests: Add missing --wait=sb to the LB I-P test.
- [dc9eb3a1](https://github.com/ovn-org/ovn/commit/dc9eb3a1cc95accc37165902006db6eeab25fba6) system-tests: Make sure that IPv6 address is available right away
- [44ee1a6c](https://github.com/ovn-org/ovn/commit/44ee1a6cb40395617f5dbab5829c9f436c16a783) Don't mention packet cloning when failing to find tunnel
- [94c8f952](https://github.com/ovn-org/ovn/commit/94c8f952bb848806e04a857a84718d2744cfcb9f) northd: Allow need frag to be SNATed
- [16bdac79](https://github.com/ovn-org/ovn/commit/16bdac7965ae805040a107fc3cdade5bf4db63a2) docs: require ovn-set-local-ip for co-located ovn-controllers
- [32ab7d94](https://github.com/ovn-org/ovn/commit/32ab7d94f9258ad6e938c715380a567b4a363a62) memory-trim: Fix timestamp overflow warning right after reboot.
- [bb8fe6ad](https://github.com/ovn-org/ovn/commit/bb8fe6add97ab5fed5e4618b32c16e174faf44c8) Fix missing flows in ls_in_dhcp_options table
- [bd32a664](https://github.com/ovn-org/ovn/commit/bd32a6646d21c766497494c7a1a4add05a40cd22) controller: throttle port claim attempts from if-status
- [d30fe25c](https://github.com/ovn-org/ovn/commit/d30fe25c45620017ceea4f06e6e3ebd316ba734f) ci: Free up additional space for ovn-k jobs.
- [42e81bdc](https://github.com/ovn-org/ovn/commit/42e81bdcebc8cd744deb8034d2fb89ec3b85bf4a) ci: Handle google-cloud-sdk -> google-cloud-cli package name change.
- [cf99264e](https://github.com/ovn-org/ovn/commit/cf99264e252c20edf93ab5735e18aa3225c98398) ci: Free up disk space in a more robust way.
- [fd79876c](https://github.com/ovn-org/ovn/commit/fd79876c2757f9074d38bd41cc36f59f3ba26138) ci: Update apt cache before installing gcc-multilib.
- [94b671cf](https://github.com/ovn-org/ovn/commit/94b671cf89b27f54d1d03149de900994c79df415) tests: fixed "send gratuitous ARP for NAT rules on HA distributed router"
- [56b0435d](https://github.com/ovn-org/ovn/commit/56b0435d8431518f4299c622a6ec9fc8770b8b0c) tests: move trim_zeros() to ovn-macros
- [14843108](https://github.com/ovn-org/ovn/commit/148431080738bdec5e625a9ce8d470e365ee14f2) tests: skip test "MAC binding aging" if scapy not available.
- [6f8719c6](https://github.com/ovn-org/ovn/commit/6f8719c60b8a578d564d3a6147f963fddeeacaa1) tests: fixed "L2 Drop and Allow ACL w/ Stateful ACL"
- [f8cdfeda](https://github.com/ovn-org/ovn/commit/f8cdfedacf212d9f103c2adba0c6805c01c68ff4) tests: fixed multiple tests missing ovn-nbctl "wait"
- [cd74dda2](https://github.com/ovn-org/ovn/commit/cd74dda22b255890a120988e8737c22a25c49957) tests: fixed "options:requested-chassis for logical port"
- [e5a794dc](https://github.com/ovn-org/ovn/commit/e5a794dc30b087e0c78764326c86a3258f97bcc0) tests: fixed "Logical router policy packet marking"
- [0575b97d](https://github.com/ovn-org/ovn/commit/0575b97dc676d8c225bc8f63befec1bf1390ebe1) tests: fixed multiple ovn-ic tests
- [b93f36a2](https://github.com/ovn-org/ovn/commit/b93f36a248f7df3eb71b5141c5deadec7c18ee24) pinctrl: Reply with correct destination for ICMPv6 RA packets
- [c4008ae5](https://github.com/ovn-org/ovn/commit/c4008ae520af2561cfd68749227a8a468277e2e5) ovn-controller: Add monitor condition for FDB.
- [d16ec6f9](https://github.com/ovn-org/ovn/commit/d16ec6f9a063a0cb2d7bac56e23dd60d0c856b76) Rename scapy-server into scapy-server.py
- [35d9e42b](https://github.com/ovn-org/ovn/commit/35d9e42bc3e60629701743ca7e9d6890511cf0f5) Add ovnkube-identity binary to the ovn-kubernetes Dockerfile
- [4a82a493](https://github.com/ovn-org/ovn/commit/4a82a49363a591d429d86d60f9120166ea04cb91) tests: offload scapy transformations to a separate unixctl daemon
- [0b45a1a1](https://github.com/ovn-org/ovn/commit/0b45a1a1cc6f081184d599ba139847ff03d90912) northd: Remove hosting-chassis only if it's specified
- [9c56ac4b](https://github.com/ovn-org/ovn/commit/9c56ac4b74f6b964f102b94404b350417b1cd772) QoS: Properly set qos when ovs db is read only
- [36f37341](https://github.com/ovn-org/ovn/commit/36f37341d32589dcd8d4bfeb023046b07dea1a44) Prepare for 23.09.1.