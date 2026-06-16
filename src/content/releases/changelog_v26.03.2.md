+++
title = "Changelog v26.03.2"
[build]
  list = 'never'
+++

### Changes from v26.03.1 to v26.03.2

- [3facc3b5](https://github.com/ovn-org/ovn/commit/3facc3b5e99ba2c863ec5f47f37466397f735802) Set release date for 26.03.2.
- [be6d85ed](https://github.com/ovn-org/ovn/commit/be6d85ed73277f4594ab8bc49693b5015911a101) system-tests: Fix flaky "Load balancer health checks - ...".
- [b1f12c5f](https://github.com/ovn-org/ovn/commit/b1f12c5fcd73df012f4878dc9b9a3dc7d77ccdc0) system-tests: Fix flaky "ECMP Flush CT entries" tests.
- [e18338cf](https://github.com/ovn-org/ovn/commit/e18338cfa5558e58b34a59fe09cad1b4fde220fa) system-tests: Cleanup NETNS_DAEMONIZE in right order.
- [dd6cd208](https://github.com/ovn-org/ovn/commit/dd6cd208a63ed8875fac19a4ea8ec41e5de07b3f) system-tests: Skip test instead of fail if module not found.
- [8942c204](https://github.com/ovn-org/ovn/commit/8942c204e244b5b68a529831b28e350c545106d0) system-tests: Fix "dynamic-routing - EVPN ... naming - Dual Stack".
- [e9322719](https://github.com/ovn-org/ovn/commit/e9322719e8cce892c2a337a8a93d3b79ccf1bf40) northd: Use uuid hash from source of parsed route.
- [ae9cf818](https://github.com/ovn-org/ovn/commit/ae9cf818192dfaf3dc64cd78d3a328575bbbcc02) northd: Fix port group I-P for recreated groups.
- [9d60b238](https://github.com/ovn-org/ovn/commit/9d60b23878c4073a25b98cc43d17c1e16aca7da4) controller: Do not remove ovn-installed from parent when deleting child port.
- [579abb5e](https://github.com/ovn-org/ovn/commit/579abb5e40ddf77005b9ce0e52964233f2a042a4) northd: Fix HM reply lflow for type=external backends on localnet LS.
- [29ea9e18](https://github.com/ovn-org/ovn/commit/29ea9e18dc46dd226c01eb64cb3d000eac594297) tests: system-ovn: Fix force SNAT IP in load-balancer template test.
- [182d4c49](https://github.com/ovn-org/ovn/commit/182d4c49800332ab52dd644fcc0242113bdfcb00) system-kmod-macros: Load modern nf_conntrack modules.
- [76153e48](https://github.com/ovn-org/ovn/commit/76153e48a02566b19181c4591300ef2d3a055788) system-kmod-macros: Do not load (t)ftp modules for non-(t)ftp tests.
- [ec348883](https://github.com/ovn-org/ovn/commit/ec348883fbc85b8d993a1bc01652d7bdaf14c9fb) tests: Fix flaky "NAT with only dnat_and_snat NAT configured" test.
- [8564cccf](https://github.com/ovn-org/ovn/commit/8564cccffb332240ee4ef6026cb024829abff1e8) system-tests: Set stable datapath-id on bridges in system tests.
- [b92b853a](https://github.com/ovn-org/ovn/commit/b92b853a01dae4821ddbc5b19a627a236f966e51) northd: Enable incremental processing for remote ports.
- [fbacd64c](https://github.com/ovn-org/ovn/commit/fbacd64c725e132b3ea2297a584b263b9445e4b5) ovn-controller: Allow two datapaths to monitor the same vrf.
- [f94604a7](https://github.com/ovn-org/ovn/commit/f94604a72d188426f6e5742c3b85da91e9b3fa91) ovn-controller: Remove unnecessary datapath plumbing from route-exchange-netlink.
- [cbb71611](https://github.com/ovn-org/ovn/commit/cbb71611b4f2f9a4e611d80606eaf153b6128aeb) northd: Clear stale LSP tags on tag_request removal.
- [e43a84b2](https://github.com/ovn-org/ovn/commit/e43a84b2198fc9f182912bedcf779b1ed12723fa) tests: Add macro for running UDP "echo" service.
- [3888f894](https://github.com/ovn-org/ovn/commit/3888f8944cf6b4f9da60622aae387dd7b9b5021a) northd: Ignore LRP.status write-only column in northd.
- [7aa8875c](https://github.com/ovn-org/ovn/commit/7aa8875cabc829e579df88c4007505d62f3d58ba) ovn-nbctl: Display tier in "acl-list" for multi-tier ACLs.
- [2a0ca98b](https://github.com/ovn-org/ovn/commit/2a0ca98b70f1e69f677c9299cf5c5922cd9b3422) ovn-nbctl: Display peer info in "show" for router ports.
- [9f04b8c5](https://github.com/ovn-org/ovn/commit/9f04b8c5086a74db299daeea4908518bbb27d139) tests: Fix flaky "Loadbalancer add-route option" system test.
- [79350ef8](https://github.com/ovn-org/ovn/commit/79350ef86e5c30e03066cb24a585bdf9fb09667c) ovn-controller: Clear flow-restore-wait.
- [afb4d33d](https://github.com/ovn-org/ovn/commit/afb4d33d6f603972ed425b8d840658f32e9d1742) tests: Remove MAC_Binding buffer limit test.
- [e480fb17](https://github.com/ovn-org/ovn/commit/e480fb1720497be68d9a40f920597b7964396770) controller: Make the packet buffering lockless.
- [f49251b7](https://github.com/ovn-org/ovn/commit/f49251b7153195269848050ba0695dbb1c605765) northd: recompute on datapath index reuse
- [86ca2816](https://github.com/ovn-org/ovn/commit/86ca28168a35ed013ee7b88bee5b6390958510e8) lflow: Always consider EVPN VTEP logical ingress/egress ports local.
- [9078d912](https://github.com/ovn-org/ovn/commit/9078d91294f455c90eb1fb7cdedce9694cc11ff7) Revert "controller: Fix bfd up too early after unexpected reboot."
- [a0a59a4c](https://github.com/ovn-org/ovn/commit/a0a59a4caffcc646040d7036279b219c27c2bfaf) tests: Ignore 'recirc_id left allocated' false positive.
- [42302941](https://github.com/ovn-org/ovn/commit/4230294124e069c5d3fa1f19d086d1601af82887) mac-cache: Make sure we re-arp for proper IP for LRP with multiple IPs.
- [a52d6068](https://github.com/ovn-org/ovn/commit/a52d606867d6040b032a1abe73b06eab699a0a03) tests: ARP to VIF port on LS with localnet port.
- [092d45d6](https://github.com/ovn-org/ovn/commit/092d45d6f472eae581ec1d71e7a42e36708fce71) northd: Revert "Process external arps on ha chassis".
- [d2ef7039](https://github.com/ovn-org/ovn/commit/d2ef703957f7904dbf6d8c11a6b2948d0f011e37) northd: Revert "Fix receiving ARP reply on non-resident chassis".
- [0b50ac21](https://github.com/ovn-org/ovn/commit/0b50ac2162f609c08ebfb3f5e7aea8ad7d200f78) northd: Revert "Fix for distributed dnat_and_snat ARP resolution".
- [11fe7bf4](https://github.com/ovn-org/ovn/commit/11fe7bf49d3de5a805c10ba4464c00861d9996af) northd: Revert "Make sure we process external ARPs even on GW routers".
- [a1ad9d5b](https://github.com/ovn-org/ovn/commit/a1ad9d5bc4ab7d18fdbfc1b4cddbdcd9ad0c4664) northd: Revert "Restrict external ARP request to logical_ip for dnat_and_snat".
- [ebf3cde8](https://github.com/ovn-org/ovn/commit/ebf3cde84bbab5826b8836cca5a842ac42bb81d6) physical: Re-evaluate CR ports when localnet port changes.
- [78cbb46e](https://github.com/ovn-org/ovn/commit/78cbb46eb6a08e16cfbaf3746ca998e2d08a179e) northd: Fix wrong logical flows for dynamically learned routes.
- [b5185a17](https://github.com/ovn-org/ovn/commit/b5185a175ed394a365d72e46dc429087173d168b) tests: Extract the common macros for send UDP and dump ARP/NS.
- [089c2fd4](https://github.com/ovn-org/ovn/commit/089c2fd418d0196bdd02b403d0f143938105453a) Fix the ovn-northd recompute loops for nb_cfg updates.
- [19d716d3](https://github.com/ovn-org/ovn/commit/19d716d3621b599beb6756495ae50305d7081d35) pinctrl: Use correct IPv6 dst for nd_ns action for IPv4 over v6.
- [6bf29d90](https://github.com/ovn-org/ovn/commit/6bf29d9049b97428b09e0f7a6ead568948759cfa) tests: Fix flaky test "Load balancer health checks - IPv4".
- [849ec030](https://github.com/ovn-org/ovn/commit/849ec03004a5cf2d63802132f59c3a9d61d190db) tests: Fix dpdk system tests not running on dual socket systems.
- [749e5998](https://github.com/ovn-org/ovn/commit/749e5998175d5f5f90e5d7c8cafd67ceb4bbebc9) pinctrl: Fix ip_mcast_sync waking up pinctrl thread too often.
- [abf17da1](https://github.com/ovn-org/ovn/commit/abf17da194bd30bac096cc6c56e5ab3eee4c777f) pinctrl: Fix garp_rarp waking up pinctrl thread too often.
- [ef57475a](https://github.com/ovn-org/ovn/commit/ef57475a8bb4723f0c829d98afe39974397bbb15) pinctrl: Add pinctrl_notify_handler_thread counter.
- [96860cc2](https://github.com/ovn-org/ovn/commit/96860cc2c78ce73ff2b8f78a3e40bf6787ca3161) ovn-controller: Skip type-update check for new port bindings.
- [85e27a2a](https://github.com/ovn-org/ovn/commit/85e27a2ab3d2403d11912961a404056fca567450) controller: Make sure that EVPN datapaths are kept across runs.
- [6a360b62](https://github.com/ovn-org/ovn/commit/6a360b62471f048c4ef5ebe85a5df1b2cb76bba2) northd: Enable ARP/ND responder for localnet-sourced requests.
- [720f0459](https://github.com/ovn-org/ovn/commit/720f0459a7d401eaf7a6520b234364ee1358e1dd) northd: Add ls_has_localnet_port() helper.
- [0d3e28a2](https://github.com/ovn-org/ovn/commit/0d3e28a2ea519598888b25b9a65d1e1f8f323dc4) tests: Fix NF flapping test.
- [bd06e7a1](https://github.com/ovn-org/ovn/commit/bd06e7a11cd52e2916d01645720c009baf653b4a) tests: Replace "unsupported protocol" test.
- [cf806ade](https://github.com/ovn-org/ovn/commit/cf806adefd4da2008beddcd4a7787cb4fd7165f9) controller: Skip frag-needed handling for VTEP ICMP packets.
- [978dc09c](https://github.com/ovn-org/ovn/commit/978dc09cfc02b3677311affe2c9c8380288a775d) expr: Fix an old copy/paste error.
- [1c1ae830](https://github.com/ovn-org/ovn/commit/1c1ae830f4e67d5a6f72402e94e62e9bfc1391eb) tests: Fix localport suppress gARP scapy input.
- [a1482006](https://github.com/ovn-org/ovn/commit/a1482006410f09dfe471c6aec76de3902327f1ad) lib: Fix dynamic_bitmap_last_set() on 32-bit architectures.
- [99a09919](https://github.com/ovn-org/ovn/commit/99a0991937ee3ec572449270de3a13b026171ddd) ovn-nb.xml: Replace Unicode em dash with ASCII comma.
- [0cc1ea5b](https://github.com/ovn-org/ovn/commit/0cc1ea5bb71d29b91244f5368ecbbda8837bc542) Prepare for 26.03.2.