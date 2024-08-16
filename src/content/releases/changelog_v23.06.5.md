+++
title = "Changelog v23.06.5"
[_build]
  list = 'never'
+++

### Changes from v23.06.4 to v23.06.5

- [503a9e35](https://github.com/ovn-org/ovn/commit/503a9e35952afa3c3c8a18c4c43a455f0e75ae69) Set release date for 23.06.5.
- [91c9c1d3](https://github.com/ovn-org/ovn/commit/91c9c1d35f6af87323ba5cf7f3190b1ec84d57b2) northd: Clean up SB MAC bindings for deleted ports.
- [16541ab0](https://github.com/ovn-org/ovn/commit/16541ab07bba84404d1d0db6bb442feb5a67f9e1) controller: Make sure the meter and group tables are initialized.
- [de49d986](https://github.com/ovn-org/ovn/commit/de49d986eadb6672f5c6adc58a9a995931878973) ci: ovn-kubernetes: Move to stable release-1.0 branch.
- [d15c6fb4](https://github.com/ovn-org/ovn/commit/d15c6fb4887961e7c3dbe9860605e04bf7f3ab92) logical-fields: Add missing multicast matches for MLD and IGMP.
- [35c71773](https://github.com/ovn-org/ovn/commit/35c71773a9ab3ba25b130a394c6f0100b594fe61) northd: Fix issues for Forwarding_Group.
- [df8d8e11](https://github.com/ovn-org/ovn/commit/df8d8e11ed5094a2e72232f78106e42c77a3043f) tests: Fix ssl-ciphers RO sb test with old openssl.
- [9e9bd2ba](https://github.com/ovn-org/ovn/commit/9e9bd2ba53786853c1aeb3fc86233838e99f99ab) controller: Store src_mac, src_ip in svc_monitor struct.
- [1c4cdc65](https://github.com/ovn-org/ovn/commit/1c4cdc654f4a2ee9bbb41efc341a72eab2be16fb) controller: Fix issue with ct_commit encode.
- [7973b415](https://github.com/ovn-org/ovn/commit/7973b41525d50d1cb86e426136c629622a21a974) northd: Skip arp-proxy flows if the lsp is a router port.
- [ab926ffe](https://github.com/ovn-org/ovn/commit/ab926ffe1b62a1a2baa67f8af8461ff63df5cc1f) ovn-controller: Initialize bitmap to zero.
- [d7398280](https://github.com/ovn-org/ovn/commit/d73982808c2059ea4686fef2dceebc7ff82f4aa8) lflow: Add missing sample flow.
- [f1dcfeef](https://github.com/ovn-org/ovn/commit/f1dcfeef80b0f55d87d778df6f0b219a19cd70ef) controller: Avoid use after free in LB I-P.
- [a92e4bb3](https://github.com/ovn-org/ovn/commit/a92e4bb38c54bba5e3c9eaf312b19eb86484995f) northd, ic: Fix handling of ovn-appctl resume.
- [05a98ef9](https://github.com/ovn-org/ovn/commit/05a98ef911b5435edb4d44d8f0f9ef002c0cec8f) Prepare for 23.06.5.