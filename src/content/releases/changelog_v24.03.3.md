+++
title = "Changelog v24.03.3"
[_build]
  list = 'never'
+++

### Changes from v24.03.2 to v24.03.3

- [459a3bab](https://github.com/ovn-org/ovn/commit/459a3bab4c4a11b904aa3c37015372d34e1e1209) Set release date for 24.03.3.
- [0690deee](https://github.com/ovn-org/ovn/commit/0690deee62d9ea271716ad87aadc33f68bec7c65) ci: Add nftables to containers.
- [fe3d7b20](https://github.com/ovn-org/ovn/commit/fe3d7b202434fa401514504cdb4608259681c0f6) tests: Skip some tests if nft not installed.
- [9d1b50e8](https://github.com/ovn-org/ovn/commit/9d1b50e8ab75e1a730905d1d99e82652c3901b36) northd: Clean up SB MAC bindings for deleted ports.
- [b01f3b59](https://github.com/ovn-org/ovn/commit/b01f3b59c6da0da0eea84a8afb346964ae3b7809) controller: Make sure the meter and group tables are initialized.
- [b4c94391](https://github.com/ovn-org/ovn/commit/b4c94391b2685266220ef9b263220c0a373ff41c) ci: ovn-kubernetes: Move to stable release-1.0 branch.
- [18d66c85](https://github.com/ovn-org/ovn/commit/18d66c8531fcb7bd2ee9abbaa99a7d6c42639ed1) logical-fields: Add missing multicast matches for MLD and IGMP.
- [2084f06a](https://github.com/ovn-org/ovn/commit/2084f06aafdac5589b7bb67ebaeb3fca4c9b7d5f) debian: Fix upper case package name in changlog.
- [fb434c5b](https://github.com/ovn-org/ovn/commit/fb434c5b9c86c5c0a6c32385761f6ef136dff0a8) northd: Fix issues for Forwarding_Group.
- [d2faeb5e](https://github.com/ovn-org/ovn/commit/d2faeb5efff1a3177e42d4df4a009807e8cd5dd4) tests: Fix ssl-ciphers RO sb test with old openssl.
- [2e11c9a6](https://github.com/ovn-org/ovn/commit/2e11c9a65130baa944a868ea920ec68ff54412b0) ci: Move common build steps into script.
- [50c329f5](https://github.com/ovn-org/ovn/commit/50c329f561eb4c6b912dd9a1c200872465a2e3dc) tests: ic: Add IP multicast test that simulates the ovn-k8s use case.
- [cdeb6c9f](https://github.com/ovn-org/ovn/commit/cdeb6c9f3e65c83584599f60956dc865792b8121) Revert "northd: Don't skip transit switch LSP when creating mcast groups."
- [c00a2c62](https://github.com/ovn-org/ovn/commit/c00a2c6254df025452e360b1c71a43f79f9f4d1a) Revert "ovn-ic: Avoid igmp/mld traffic flooding."
- [4d47713d](https://github.com/ovn-org/ovn/commit/4d47713d8b229d53243fd46e5a809567ed8dc692) Revert "IC: Tansit switch don't flood mcast traffic to router ports if matches igmp group."
- [02cda45a](https://github.com/ovn-org/ovn/commit/02cda45a02dcc4e88a2608aee5c6a1f4e50f2cba) controller: Send RARP/GARP for VIF post link state is up.
- [bcbd0972](https://github.com/ovn-org/ovn/commit/bcbd09724f441b6df7412da8c3d53b9d7ba72572) controller: Store src_mac, src_ip in svc_monitor struct.
- [a8a4b87e](https://github.com/ovn-org/ovn/commit/a8a4b87e1873e67c4e78ce7857e352059bc2aa5e) controller: Fix issue with ct_commit encode.
- [57e8d78f](https://github.com/ovn-org/ovn/commit/57e8d78f5beeefcd99297ae87c6505fc20f7b45a) northd: Skip arp-proxy flows if the lsp is a router port.
- [b1c55c42](https://github.com/ovn-org/ovn/commit/b1c55c42f8961d88b7a0f9a8b7e6d46a0fcf81c3) ovn-nbctl: Show bfd option man for lr-policy-add command.
- [233b105b](https://github.com/ovn-org/ovn/commit/233b105b20a389b984365521ed5c67ca0ec1ae2d) ovn-controller: Initialize bitmap to zero.
- [ffe02579](https://github.com/ovn-org/ovn/commit/ffe02579c71489e3aa0858ab0ff09702863f6f4b) lflow: Add missing sample flow.
- [ff11ab41](https://github.com/ovn-org/ovn/commit/ff11ab416c230ee36c18b52d86a505a27cb932c8) northd: Fix an issue wrt mac binding aging.
- [7b65a654](https://github.com/ovn-org/ovn/commit/7b65a65402963caf1cf7ff1b2152290f02277750) ci: Pin Fedora version for the build-rpm job.
- [0440a083](https://github.com/ovn-org/ovn/commit/0440a083d2bb024fe3a8263f72c7c749cc9fae5a) controller: Avoid use after free in LB I-P.
- [bc2af6ab](https://github.com/ovn-org/ovn/commit/bc2af6ab81b47cb5303efb072f56dfe3ec149649) northd, ic: Fix handling of ovn-appctl resume.
- [9c8264e7](https://github.com/ovn-org/ovn/commit/9c8264e765548f7c2f2e15af217c84abc664b932) Prepare for 24.03.3.