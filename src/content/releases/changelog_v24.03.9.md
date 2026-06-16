+++
title = "Changelog v24.03.9"
[build]
  list = 'never'
+++

### Changes from v24.03.8 to v24.03.9

- [bd3baf44](https://github.com/ovn-org/ovn/commit/bd3baf441086577057e31b19dd616f878a478702) Set release date for 24.03.9.
- [5ff3857c](https://github.com/ovn-org/ovn/commit/5ff3857c3ce20de49e9f635f99fb42ee7f6c2042) system-tests: Cleanup NETNS_DAEMONIZE in right order.
- [1d2d67e0](https://github.com/ovn-org/ovn/commit/1d2d67e03f87c1b747bdc93bf85eb3b832b00037) system-tests: Skip test instead of fail if module not found.
- [9204ec37](https://github.com/ovn-org/ovn/commit/9204ec37bf7de0c31c8caf94bc28df2a08904c1f) tests: system-ovn: Fix force SNAT IP in load-balancer template test.
- [09af5a17](https://github.com/ovn-org/ovn/commit/09af5a1753da795b1679895f558aa9e9d54f3275) system-kmod-macros: Load modern nf_conntrack modules.
- [459cfe69](https://github.com/ovn-org/ovn/commit/459cfe6926d766483178db18ea60f5ab9f81981a) system-kmod-macros: Do not load (t)ftp modules for non-(t)ftp tests.
- [5ab533a5](https://github.com/ovn-org/ovn/commit/5ab533a54616cbf172634cf19e3b6ca2b30195f4) system-tests: Set stable datapath-id on bridges in system tests.
- [bcfb4b46](https://github.com/ovn-org/ovn/commit/bcfb4b46ab3e2c1cd085982e77c4988764818bd6) northd: Ignore LRP.status write-only column in northd.
- [b04f7a8a](https://github.com/ovn-org/ovn/commit/b04f7a8a3206145ad72d223b12d0a9d5ed60f5df) ovn-nbctl: Display tier in "acl-list" for multi-tier ACLs.
- [d023b02d](https://github.com/ovn-org/ovn/commit/d023b02de8074fb2637ef4ae400db826501c3f7d) ovn-nbctl: Display peer info in "show" for router ports.
- [28a3da73](https://github.com/ovn-org/ovn/commit/28a3da73f16e742ae89e2e2888281008435efef4) tests: Fix flaky "Loadbalancer add-route option" system test.
- [97f93c3f](https://github.com/ovn-org/ovn/commit/97f93c3f111d74b8231b8466c359b0739209442b) ovn-controller: Clear flow-restore-wait.
- [7d5b6f90](https://github.com/ovn-org/ovn/commit/7d5b6f90f21bcd756cf29d3f2afee446bb654d54) Revert "controller: Fix bfd up too early after unexpected reboot."
- [52e60a84](https://github.com/ovn-org/ovn/commit/52e60a84b14ff0f9abd6c6d192896f8d39675d4e) tests: Ignore 'recirc_id left allocated' false positive.
- [ed55f701](https://github.com/ovn-org/ovn/commit/ed55f7012659c0058a6093429afaea224c2b5cd8) mac-cache: Make sure we re-arp for proper IP for LRP with multiple IPs.
- [663f0f5b](https://github.com/ovn-org/ovn/commit/663f0f5b8c6ebe0bbf3ab343da32b692d59def73) tests: Extract the common macros for send UDP and dump ARP/NS.
- [9d78ef7a](https://github.com/ovn-org/ovn/commit/9d78ef7af9de4d156f4c3eafe325c90cd1e3d891) Fix the ovn-northd recompute loops for nb_cfg updates.
- [20ee3d9a](https://github.com/ovn-org/ovn/commit/20ee3d9a087e2a2a9816d2c10f0ce694862e1802) northd: Enable ARP/ND responder for localnet-sourced requests.
- [d035a76d](https://github.com/ovn-org/ovn/commit/d035a76d42d369d4a7ffbe84a250ab7bcd7adf25) expr: Fix an old copy/paste error.
- [ee31a04b](https://github.com/ovn-org/ovn/commit/ee31a04b5a148c143d0f59e6284eba3f07237c3e) tests: Fix localport suppress gARP scapy input.
- [bd0ef4f4](https://github.com/ovn-org/ovn/commit/bd0ef4f4c7ee6329b0d8f209669d53675c94653c) Prepare for 24.03.9.