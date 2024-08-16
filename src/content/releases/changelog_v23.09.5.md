+++
title = "Changelog v23.09.5"
[_build]
  list = 'never'
+++

### Changes from v23.09.4 to v23.09.5

- [65822768](https://github.com/ovn-org/ovn/commit/6582276862c7c1b7bbf879f0af0ce350a9253a78) Set release date for 23.09.5.
- [23b86e41](https://github.com/ovn-org/ovn/commit/23b86e41ab8c91b10b9e187a1ebfef8f41ec0fe5) ci: Add nftables to containers.
- [e43b9140](https://github.com/ovn-org/ovn/commit/e43b9140e5f8f02cf86e06d69ed9c0df5d01989a) tests: Skip some tests if nft not installed.
- [4a98b76f](https://github.com/ovn-org/ovn/commit/4a98b76fe4dec6029002b7c67c91a8120583006d) northd: Clean up SB MAC bindings for deleted ports.
- [563f0b7d](https://github.com/ovn-org/ovn/commit/563f0b7d2a70f903f43679b18b025e10572c3332) controller: Make sure the meter and group tables are initialized.
- [8e4f3ff2](https://github.com/ovn-org/ovn/commit/8e4f3ff204db3a577306f0455e2de99662d284b0) ci: ovn-kubernetes: Move to stable release-1.0 branch.
- [ea584fd6](https://github.com/ovn-org/ovn/commit/ea584fd60936997cd15f2d9d3340d62c1f3b5ace) logical-fields: Add missing multicast matches for MLD and IGMP.
- [3cbd4d8e](https://github.com/ovn-org/ovn/commit/3cbd4d8e1f3c699bc378e0cab6ae980cef8725cf) northd: Fix issues for Forwarding_Group.
- [aa4cd0cd](https://github.com/ovn-org/ovn/commit/aa4cd0cdd0df5d4dd202bf089f7ff6db58732a9d) tests: Fix ssl-ciphers RO sb test with old openssl.
- [dca6e187](https://github.com/ovn-org/ovn/commit/dca6e187d6e63c6f37111aeddb05517886481751) ci: Move common build steps into script.
- [83c2238c](https://github.com/ovn-org/ovn/commit/83c2238cbf41f6600fe024ce1df58c9800299bd6) northd: ic: Remove unused function and fix unit test.
- [5f0809be](https://github.com/ovn-org/ovn/commit/5f0809be565713d3634a6c663e122c0bfb5dff92) Revert "northd: Don't skip transit switch LSP when creating mcast groups."
- [848b17e9](https://github.com/ovn-org/ovn/commit/848b17e907a6d8d333c8d995994d524951ad0efd) Revert "ovn-ic: Avoid igmp/mld traffic flooding."
- [dc62643b](https://github.com/ovn-org/ovn/commit/dc62643b9cb2eaa3e91bd8df4588d0b8e2aad16c) Revert "IC: Tansit switch don't flood mcast traffic to router ports if matches igmp group."
- [0539de39](https://github.com/ovn-org/ovn/commit/0539de39078ee018fe5a6962d6f2950cec0860fb) controller: Send RARP/GARP for VIF post link state is up.
- [d20498c4](https://github.com/ovn-org/ovn/commit/d20498c4ef621934f0fb3a416c032313f29c6688) controller: Store src_mac, src_ip in svc_monitor struct.
- [24e0e2dc](https://github.com/ovn-org/ovn/commit/24e0e2dc3bcac752480c958afd0d23420be3b5d4) controller: Fix issue with ct_commit encode.
- [cf6cd0f5](https://github.com/ovn-org/ovn/commit/cf6cd0f579495906ac189b4b054eb5d5276eda20) northd: Skip arp-proxy flows if the lsp is a router port.
- [76d7a30f](https://github.com/ovn-org/ovn/commit/76d7a30f6652c9da81c81178ca5eddbf24d81323) ovn-controller: Initialize bitmap to zero.
- [fb8b5891](https://github.com/ovn-org/ovn/commit/fb8b58913f5275563d8f80ea3658d8c5dfe55d03) lflow: Add missing sample flow.
- [a8b1a532](https://github.com/ovn-org/ovn/commit/a8b1a53244ef885f840be848ae99bf4e406a96ff) controller: Avoid use after free in LB I-P.
- [d929ea79](https://github.com/ovn-org/ovn/commit/d929ea791822c502989a688a1687fbbc6950d92f) northd, ic: Fix handling of ovn-appctl resume.
- [d70ff693](https://github.com/ovn-org/ovn/commit/d70ff69318f4ef4553ee1da32345d5243525b698) Prepare for 23.09.5.