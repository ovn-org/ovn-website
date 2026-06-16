+++
title = "Changelog v25.09.4"
[build]
  list = 'never'
+++

### Changes from v25.09.3 to v25.09.4

- [91047c65](https://github.com/ovn-org/ovn/commit/91047c65bc3743a365f186529edffa24f2cd3b9a) Set release date for 25.09.4.
- [f8314330](https://github.com/ovn-org/ovn/commit/f8314330e5bcc3c6639045ec87b447f03740f9c9) system-tests: Fix flaky "ECMP Flush CT entries" tests.
- [3dc6e2ca](https://github.com/ovn-org/ovn/commit/3dc6e2caee54a0392330ca6f5ce1e8b145567611) system-tests: Cleanup NETNS_DAEMONIZE in right order.
- [47aa6332](https://github.com/ovn-org/ovn/commit/47aa63323c4c0587776af5ab4d433cd5fae2335c) system-tests: Skip test instead of fail if module not found.
- [6fd646b8](https://github.com/ovn-org/ovn/commit/6fd646b86f71ca8078b9e0e80f61b9aa3152f63e) northd: Use uuid hash from source of parsed route.
- [3a1dda95](https://github.com/ovn-org/ovn/commit/3a1dda95a3cffedffbd712a5495ffa9d20f7695f) northd: Fix port group I-P for recreated groups.
- [3923fe7c](https://github.com/ovn-org/ovn/commit/3923fe7c202c2ba31e75e43199a58f18d4294d76) tests: system-ovn: Fix force SNAT IP in load-balancer template test.
- [fb2e24e5](https://github.com/ovn-org/ovn/commit/fb2e24e5af507ac58e59bb004e125437c215013f) system-kmod-macros: Load modern nf_conntrack modules.
- [4d8b1bbd](https://github.com/ovn-org/ovn/commit/4d8b1bbde8b81d4dc1ddbe03eeb55f174f51d4b5) system-kmod-macros: Do not load (t)ftp modules for non-(t)ftp tests.
- [2b453ead](https://github.com/ovn-org/ovn/commit/2b453eadcd5306fcc060b53e26bd98b7ef39c474) tests: Fix flaky "NAT with only dnat_and_snat NAT configured" test.
- [04f86dbb](https://github.com/ovn-org/ovn/commit/04f86dbb40f86a3ceba9dc8009f4c224e39ffc7a) system-tests: Set stable datapath-id on bridges in system tests.
- [0e280268](https://github.com/ovn-org/ovn/commit/0e2802685f24ef3c07dfa3e073b9673f229011bb) northd: Enable incremental processing for remote ports.
- [81626613](https://github.com/ovn-org/ovn/commit/81626613b2c3a6412c931933781b8d0bd0595096) northd: Ignore LRP.status write-only column in northd.
- [454fdb1b](https://github.com/ovn-org/ovn/commit/454fdb1b1127a2e093a4011b5fa8fc2b299171c4) ovn-nbctl: Display tier in "acl-list" for multi-tier ACLs.
- [04cc9b30](https://github.com/ovn-org/ovn/commit/04cc9b30eb9d1a5b849d1224210a725538a32fba) ovn-nbctl: Display peer info in "show" for router ports.
- [21f3006e](https://github.com/ovn-org/ovn/commit/21f3006e0d7f22eda5d36b19d7b0698066d6cce4) tests: Fix flaky "Loadbalancer add-route option" system test.
- [a21b011e](https://github.com/ovn-org/ovn/commit/a21b011ee922f204af9a55f724883dc7eeebdfcc) ovn-controller: Clear flow-restore-wait.
- [981535ff](https://github.com/ovn-org/ovn/commit/981535ffcbe6c2170da90f01351b40118587ecae) Revert "controller: Fix bfd up too early after unexpected reboot."
- [30c675c1](https://github.com/ovn-org/ovn/commit/30c675c1086dfceaf13ba45162d172f07b68df4b) tests: Ignore 'recirc_id left allocated' false positive.
- [c73c9676](https://github.com/ovn-org/ovn/commit/c73c9676c83ef008cfc813fe6a8c8f1781478ab2) mac-cache: Make sure we re-arp for proper IP for LRP with multiple IPs.
- [8a530c73](https://github.com/ovn-org/ovn/commit/8a530c7387cbba246b3485d606a9cca4629f0a7e) physical: Re-evaluate CR ports when localnet port changes.
- [aba711e6](https://github.com/ovn-org/ovn/commit/aba711e6603e03bcdcacd85590e4232193df2d9e) northd: Fix wrong logical flows for dynamically learned routes.
- [4422ee01](https://github.com/ovn-org/ovn/commit/4422ee01ffa49e3524c26bed9b9f5547c686e900) tests: Extract the common macros for send UDP and dump ARP/NS.
- [8cd13a75](https://github.com/ovn-org/ovn/commit/8cd13a754d22816a30218dfcf749ec1edc057454) Fix the ovn-northd recompute loops for nb_cfg updates.
- [1be1da07](https://github.com/ovn-org/ovn/commit/1be1da079b5c46e5f6a8446f09c5f95c67e3a37c) pinctrl: Use correct IPv6 dst for nd_ns action for IPv4 over v6.
- [7ba4933d](https://github.com/ovn-org/ovn/commit/7ba4933d8f4b23b61e53253cabce57bddc9ea7a0) tests: Fix flaky test "Load balancer health checks - IPv4".
- [d7e7f5bd](https://github.com/ovn-org/ovn/commit/d7e7f5bd6837ff004136aca5add340e91ce6dc65) tests: Fix dpdk system tests not running on dual socket systems.
- [30fb8c93](https://github.com/ovn-org/ovn/commit/30fb8c93631b43e13ebb7e3e52fe6943b5bfc104) pinctrl: Fix ip_mcast_sync waking up pinctrl thread too often.
- [e6ee5248](https://github.com/ovn-org/ovn/commit/e6ee52487d13f3db7767e612992976fbe958fc9d) pinctrl: Fix garp_rarp waking up pinctrl thread too often.
- [231c9bd8](https://github.com/ovn-org/ovn/commit/231c9bd87c71aeedf93e43bac9e5642cf77f7836) pinctrl: Add pinctrl_notify_handler_thread counter.
- [ac963bdc](https://github.com/ovn-org/ovn/commit/ac963bdc723f19cbef505b21ed15b6f0a13ff00d) ovn-controller: Skip type-update check for new port bindings.
- [39ca8ea0](https://github.com/ovn-org/ovn/commit/39ca8ea002c7bf08ba7aef77191e645929c1b682) northd: Enable ARP/ND responder for localnet-sourced requests.
- [82f65bd8](https://github.com/ovn-org/ovn/commit/82f65bd8cb58ea4092a74a2d33c4fa388e7cca25) northd: Add ls_has_localnet_port() helper.
- [5ba44822](https://github.com/ovn-org/ovn/commit/5ba4482211667f93d4c303307219acf6acdbb33d) expr: Fix an old copy/paste error.
- [47213567](https://github.com/ovn-org/ovn/commit/47213567bebafab097214e56e684fb0bb170e82e) tests: Fix localport suppress gARP scapy input.
- [44d05d39](https://github.com/ovn-org/ovn/commit/44d05d39ea8b9decc85fd4d6bc6404919ba5ea9b) Prepare for 25.09.4.