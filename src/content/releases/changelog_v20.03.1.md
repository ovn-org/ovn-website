+++
title = "Changelog v20.03.1"
[_build]
  list = 'never'
+++

### Changes from v20.03.0 to v20.03.1

- [5d915e75](https://github.com/ovn-org/ovn/commit/5d915e75b1d4e9e34a66b941bf629a28375e1f74) Correct release date for 20.03.1
- [55f4a823](https://github.com/ovn-org/ovn/commit/55f4a823bb7d4627d36db5b0b16dbc32c91e0db6) Make the notify() calls work with IPv6 in the OCF resource-agent
- [82c08be3](https://github.com/ovn-org/ovn/commit/82c08be3d55ce88060ffe2debdd1762fa1a911f3) controller: fix ip buffering with static routes
- [f7050af5](https://github.com/ovn-org/ovn/commit/f7050af5d452c6e99d5385b89c3496722bd5106c) controller: Free the qos hmap built in binding_run().
- [0a6e9124](https://github.com/ovn-org/ovn/commit/0a6e91249414d789d77c1782130ed919cb43a1d1) ovn-northd: Fix memory leak in case of distributed NAT.
- [76b7f146](https://github.com/ovn-org/ovn/commit/76b7f14632642fa03522ee490fd1d4ccf4c9f5ee) ofctrl: Fix using uninitialized flow cookie.
- [9d3efe47](https://github.com/ovn-org/ovn/commit/9d3efe47643d8f70a21adc8db2decbcda86e4f1e) ovn-northd: Fix memory leak in case of duplicate logical router port.
- [95f7719a](https://github.com/ovn-org/ovn/commit/95f7719a7ed5acbbc4bf84c81740c231a41b9b08) pinctrl: Fix icmp6 packet corruption issue
- [18d3c8e2](https://github.com/ovn-org/ovn/commit/18d3c8e2a0c3b16e7286ccd2f7d56dfd3a645488) rhel: Fix ovn-controller-vtep systemd-unit parameter
- [2d5a3b82](https://github.com/ovn-org/ovn/commit/2d5a3b826fcba9ae7621be992fa670a697370ae5) Fix typo for validation of logical ip in ipv6 mode.
- [8e503d9b](https://github.com/ovn-org/ovn/commit/8e503d9bf0718a9eacdddbad280743642759df8e) Fix ACL reject action for UDP packets.
- [37884b61](https://github.com/ovn-org/ovn/commit/37884b61b953d90e8e1486fe9db9c2bbade4b081) ovn-northd: Fix memory leak and incorrect limiting of ECMP routes.
- [1d0f3444](https://github.com/ovn-org/ovn/commit/1d0f34448bf965c160ab67f5d212abcb609b1869) ovn-northd: Fix tunnel_key allocation for SB Port_Bindings.
- [06859410](https://github.com/ovn-org/ovn/commit/068594107bfb92edd9ccd94ac8cd69d0f23204bd) ovn-northd: Clear SB records depending on stale datapaths.
- [90e56a50](https://github.com/ovn-org/ovn/commit/90e56a5072544170cff618f6f64559303011f323) test-tcp-rst.py: Fix flake8 errors.
- [7aedc2e0](https://github.com/ovn-org/ovn/commit/7aedc2e0f619b424e1e6e42f1e7a363404aedbe4) Rely on unique name for ovn qos meters
- [4422f17b](https://github.com/ovn-org/ovn/commit/4422f17b3792e1d6bdf1b192020e2bdf922e311f) ovn-northd: Optimize flows for LB Hairpin traffic.
- [5cdc424c](https://github.com/ovn-org/ovn/commit/5cdc424c87c17c5c0711b55982139703f580d5d0) Fix conntrack entry leaks because of TCP RST packets not sent to conntrack.
- [ac9b59da](https://github.com/ovn-org/ovn/commit/ac9b59da8f5b49d82b06b1c4d7acc48b4811aaf3) ovn.at: Add check for routed IPv6 ND packets.
- [0924bcb0](https://github.com/ovn-org/ovn/commit/0924bcb07ef25f93fde683fe8f15d376eca005ec) ovn-northd: Limit IPv6 ND NS/RA/RS to the local network.
- [35880323](https://github.com/ovn-org/ovn/commit/35880323525e83b4933fbb9b0df471af85798211) pinctrl: Handle service monitors even if the lport doesn't have IPv4 addresses set.
- [29927708](https://github.com/ovn-org/ovn/commit/29927708242044696a49051c77c3d4b38ba02392) ovn-nbctl: Create daemon control socket in ovn run dir
- [523b1f5f](https://github.com/ovn-org/ovn/commit/523b1f5f45682bd6dd454281a97a09c3f429c457) ovn-controller: Skip vport bindings done through OVS external_ids:iface-id.
- [5b3e9879](https://github.com/ovn-org/ovn/commit/5b3e9879be2b6c9b07ed5c9e073f1c24080a49f7) ovn-controller: Fix potential segfault with "virtual" port bindings.
- [3cf40e8b](https://github.com/ovn-org/ovn/commit/3cf40e8b35c5d6a4e593b42b96c284a8742235d5) ovn-northd: Skip unsnat flows for load balancer vips in router ingress pipeline
- [20aa8c3c](https://github.com/ovn-org/ovn/commit/20aa8c3c5a1930805a32ec8121affa07b2ac7dff) northd: do not insert identical lflows in S_ROUTER_IN_ARP_RESOLVE
- [c17d3bee](https://github.com/ovn-org/ovn/commit/c17d3bee83c9f19235a274d9aa0f6be1fe84a70c) ovn.at: Fix ARP test that fails due to timing.
- [9f13732a](https://github.com/ovn-org/ovn/commit/9f13732ae232aa0c872527d948435125b3a6cbce) ovn-northd: Forward ARP requests on localnet ports.
- [f70a0f7c](https://github.com/ovn-org/ovn/commit/f70a0f7c485f13cbbae8bc6f8d78225238c308b9) ovn-northd: Add lflows to by pass the svc monitor packets from conntrack.
- [458b19ed](https://github.com/ovn-org/ovn/commit/458b19ed40a499a4c0d6288b53be9da1a5fb3132) travis: Disable sindex build in sparse.
- [f4497bb8](https://github.com/ovn-org/ovn/commit/f4497bb87ca59daff9a0be3eeea157376275516d) travis: Avoid skipping of interconnection tests.
- [5dcd8d77](https://github.com/ovn-org/ovn/commit/5dcd8d77f01513defe9d2bb23b5b99ca289faf89) travis: Obtain testsuite logs from the correct directory.
- [bd2475fb](https://github.com/ovn-org/ovn/commit/bd2475fb5a681cb62d97c0456525bbf882029e21) travis: Dump config.log if make fails.
- [a102c63e](https://github.com/ovn-org/ovn/commit/a102c63e346c25379a3766047941e6138d495983) logical-fields: fix memory leak caused by initialize ovnfield_by_name twice
- [4f8045b3](https://github.com/ovn-org/ovn/commit/4f8045b3b5f2c3376f86f5edc4e3f7507c2b1148) Broadcast DHCPREPLY when BROADCAST flag is set
- [1f676ab8](https://github.com/ovn-org/ovn/commit/1f676ab84b6a7e1f2792c2450aa543334126eecc) system tests: Fix occasional failure of the test - "Load balancer health checks".
- [58027fe3](https://github.com/ovn-org/ovn/commit/58027fe3b275584257f6e8e346f85aca32fa2ca8) Prepare for 20.03.1