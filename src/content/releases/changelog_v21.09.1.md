+++
title = "Changelog v21.09.1"
[_build]
  list = 'never'
+++

### Changes from v21.09.0 to v21.09.1

- [ce6a75b9](https://github.com/ovn-org/ovn/commit/ce6a75b9ef49173e13820fa796fc84bf7995afae) Set release date for 21.09.1.
- [17c9f04d](https://github.com/ovn-org/ovn/commit/17c9f04d6d73644cc5e726258623cf8d2653f0ff) ovs: Bump submodule to include ovsdb/IDL optimizations.
- [37f2027c](https://github.com/ovn-org/ovn/commit/37f2027c3c4af42bc4d98fdc81ed0b65fbde2725) ovn-nbctl: Fix lrp-set-gateway-chassis.
- [2c68361d](https://github.com/ovn-org/ovn/commit/2c68361d4379a6f86b8197f298ca21c754c4843e) ovn-trace: Set ct_state if not already set when tracing ct(nat).
- [20688808](https://github.com/ovn-org/ovn/commit/20688808f467d888bee234632fe2eda15eeaa1e2) northd: Don't add ARP responder flows for unreachable VIPs.
- [7fd0e56d](https://github.com/ovn-org/ovn/commit/7fd0e56df6f92ba1f4e80c54fdb3b6b5554ad480) northd: Treat reachable and unreachable VIPs differently.
- [323f036d](https://github.com/ovn-org/ovn/commit/323f036db9c69fed406c463c4de5b4b366503fb1) northd: Always generate valid load balancer address set names.
- [3b4a220e](https://github.com/ovn-org/ovn/commit/3b4a220eca6001b2aba92b56a6f7848c382cff97) nb: Add support for Load_Balancer_Groups.
- [7191e16f](https://github.com/ovn-org/ovn/commit/7191e16f1241dd9bc4eaf9bb6189186dc6280f21) northd: Use address sets for ARP responder flows for VIPs.
- [c941150b](https://github.com/ovn-org/ovn/commit/c941150b2595f0e96954fc6a3cf51e3c03ed3fa9) ci: Remove generating ovn-k8s test report.
- [df2eebc3](https://github.com/ovn-org/ovn/commit/df2eebc353f5e6e3b6ed2cac2eb3eee2a05af5ab) northd: fix check_pkt_larger ingress flows with FIP
- [8171e0e1](https://github.com/ovn-org/ovn/commit/8171e0e159f4dda67b54b54436ec7683f76bd697) ovn.at: Fix flaky test "router - check packet length - icmp defrag"
- [589e6277](https://github.com/ovn-org/ovn/commit/589e6277f66a07ce470c26bbd74a502824d545f0) ovn-northd: Treat reachable and unreachable addresses identically.
- [e2075cc5](https://github.com/ovn-org/ovn/commit/e2075cc5bc5e4628c5cce2e0d8d37042cf80d869) ci: Make linux-prepare trust system installs.
- [ac56a8d1](https://github.com/ovn-org/ovn/commit/ac56a8d1d6516baac36933918dc5b2a47bf64a99) northd.c: Fix northd blocking on deleting duplicated SB datapath.
- [7df9287e](https://github.com/ovn-org/ovn/commit/7df9287e4a7d8bc5fb94f67448774b92d3ce0b86) controller: bfd: do not always wake main thread in bfd_check_detection_timeout
- [77b6e809](https://github.com/ovn-org/ovn/commit/77b6e809c57ee74b618a930d5e2be5e4e85a799e) libs: Replace weak with strong compare and exchange
- [e2682662](https://github.com/ovn-org/ovn/commit/e26826629e984a73c662ea48308556d76fe6a186) Deliver multicast traffic to localport ports
- [988ca6c4](https://github.com/ovn-org/ovn/commit/988ca6c4bb6363bd9781279459b11b96a89831c1) controller: do not mark bfd and ipv6_pd msgs as local-only
- [43f852e7](https://github.com/ovn-org/ovn/commit/43f852e74041d13af3c99c63f0a2628df0d0f6c6) tests: fix flaky "ovn-ic -- gateway sync" test
- [fc0ed8c1](https://github.com/ovn-org/ovn/commit/fc0ed8c19c3563172c4189640578eb635d47b338) northd: do not run find_lrp_member_ip with empty nexthop
- [6b7524f9](https://github.com/ovn-org/ovn/commit/6b7524f9d05b37421422e19b1b9e0975a9be16ca) northd.c: Lock to protect against possible od->group corruption.
- [e1ecacbc](https://github.com/ovn-org/ovn/commit/e1ecacbca62dbe89beccb6ae030a53f07bad8f85) northd.c: Remove redundant condition check in ovn_dp_group_add_with_reference().
- [11fb404e](https://github.com/ovn-org/ovn/commit/11fb404e06c63f0bbc7e871302c1f577c8063a91) test: Fix options:requested-chassis with hostname
- [dd1b4b4d](https://github.com/ovn-org/ovn/commit/dd1b4b4d48a6378a20bb615db4cfbcaf82db034f) Fix basic multicast flows for vxlan (non-vtep) tunnels
- [e97416f1](https://github.com/ovn-org/ovn/commit/e97416f14389bd1b72a88608ed19376ae71a101d) Enforce datapath and port key constraints in vxlan mode
- [48772e62](https://github.com/ovn-org/ovn/commit/48772e622ef47fb0a21bb77d1d306d032c875bc1) Prepare for 21.09.1.