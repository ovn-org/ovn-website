+++
title = "Changelog v25.09.5"
[build]
  list = 'never'
+++

### Changes from v25.09.4 to v25.09.5

- [477c5be5](https://github.com/ovn-org/ovn/commit/477c5be5bb6c71e4b68a5fe4ce5733a50c0c9d8e) Set release date for 25.09.5.
- [a74518d1](https://github.com/ovn-org/ovn/commit/a74518d1abea93f254918686c6d7c9eb0134187b) controller: Resync netlink tables after missed notifications.
- [48474e27](https://github.com/ovn-org/ovn/commit/48474e276e350ac6708d88ec0556871acf6b970d) tests: Mark "MAC binding aging - probing GW router Dynamic Neigh" unstable.
- [0ce2e5ce](https://github.com/ovn-org/ovn/commit/0ce2e5ceba5a9068b7ff152e0be46367dd605d0c) northd: Ignore VTEP chassis when evaluating chassis features.
- [816e1a3d](https://github.com/ovn-org/ovn/commit/816e1a3d1b3ecc375dfc9ae048c67cef053bcd75) tests: Fix MAC binding probing flakiness.
- [7826dc40](https://github.com/ovn-org/ovn/commit/7826dc40ae02585942c2f6dfb22e039472fd386f) tests: Fix flaky "Mirror - lport: 2 HVs, 2 LS, 1 lport/LS...".
- [7e812b41](https://github.com/ovn-org/ovn/commit/7e812b416f4f9f923f14e1909f790c48932c6985) treewide: Fix imcp typo.
- [76fe9607](https://github.com/ovn-org/ovn/commit/76fe9607b7b173df797400af2c41b0ff0ce0e211) mac-cache: Use packet count to check if flow is active.
- [1699f933](https://github.com/ovn-org/ovn/commit/1699f933b1044d05ab0a8fff89cfc6f82b32f798) mac-cache: Do not send probes for inactive MAC Bindings.
- [77cd5b40](https://github.com/ovn-org/ovn/commit/77cd5b40d4a248050607f4b657507accdc83be90) sync-meters: Do not recompute if both log and meters are not set.
- [b5aa4445](https://github.com/ovn-org/ovn/commit/b5aa44456cd89fd4d59bfbe83e3f193f6765f03f) lflow: Lift the reply limitation for ARP mac_cache_use flows.
- [1a8b63c4](https://github.com/ovn-org/ovn/commit/1a8b63c4b6cd2cb5d47688ebd4697c787920c7dd) ofctrl: Don't defer flow update acknowledgement.
- [1f0c7764](https://github.com/ovn-org/ovn/commit/1f0c7764a19a9f23ecdda4d0a5d96baf589e17e2) northd: Skip UNSNAT for force-SNAT load balancer VIPs.
- [f7a907dc](https://github.com/ovn-org/ovn/commit/f7a907dca7e6ba7d796d00834be5f9e34cf4817e) northd: Support /31 router ports (RFC 3021).
- [a1b7c8d0](https://github.com/ovn-org/ovn/commit/a1b7c8d001abd73f0275e55dc3d7e979dba18932) tests: Add missing check for ovn-nbctl in ovn-ic.at.
- [332e32d2](https://github.com/ovn-org/ovn/commit/332e32d24d4b5b720a1748ddcbf3963f4dd05e45) checkpatch: Ensure ovn_as az-x ovn-nbctl/sbctl have a check.
- [d81a5c67](https://github.com/ovn-org/ovn/commit/d81a5c673c408d589d0ba65ef62bf1f7e7a4143e) tests: Fix flaky "Routing protocol control plane redirect" test.
- [2314091e](https://github.com/ovn-org/ovn/commit/2314091ea91a6f6653c6aaeaac4455d21421dfb5) northd: Fix Crash when deleting ports with BFD session.
- [2a5c6b51](https://github.com/ovn-org/ovn/commit/2a5c6b51910099393bed2f986ace408349fae2c0) northd: Make sure we learn from ND NS as we do with ARP requests.
- [7f00af77](https://github.com/ovn-org/ovn/commit/7f00af7786ff7ab5d999afc6cc5ad6066833cb5c) controller: Flush dynamic routes learned in uninterested LRP.
- [8968ec5d](https://github.com/ovn-org/ovn/commit/8968ec5d8f5e6fcafb5ec04d7ff5a92f00eff89b) test: Mark the SB Disconnect - MAC_Binding buffer limit as not upgradable.
- [5c1782c2](https://github.com/ovn-org/ovn/commit/5c1782c2d28c93128114a521ea61c298392ec020) northd: Make sure lookup_nd works with ND if nd.tll is 0.
- [b9a1a405](https://github.com/ovn-org/ovn/commit/b9a1a405a8cdfef3fb4343d947fbbda660c01814) ci: Update crun to 1.28 in GitHub actions runner.
- [484480bc](https://github.com/ovn-org/ovn/commit/484480bcbba2ddf704d25e28fd82b7ebd350a32d) northd: Restrict ARP/ND_NS L2 lookup flows to broadcast.
- [f2557ab5](https://github.com/ovn-org/ovn/commit/f2557ab57285c1d6aedcbe5f409ce34b23e5a0a9) northd: Use MC_UNKNOWN for broadcast ARP requests.
- [82a3c8ed](https://github.com/ovn-org/ovn/commit/82a3c8eda5146dcaa04a550c61615d9ebf995d0e) tests: Use a native UDP server for ACL sampling.
- [17d719fc](https://github.com/ovn-org/ovn/commit/17d719fc1c81baa4b6d180a95a15ef1c6285aafe) tests: Send CoPP Scapy traffic at layer 2.
- [02d9160d](https://github.com/ovn-org/ovn/commit/02d9160d4c2a06a1e622d561b7005ff39d28577e) tests: Find cat through PATH.
- [a666ae97](https://github.com/ovn-org/ovn/commit/a666ae97fe0760d2d3e7df0607fdea053e6824c6) tests: Use explicit schemes for Wget URLs.
- [9d441c31](https://github.com/ovn-org/ovn/commit/9d441c31f70cd3d065be5c34de5c629b33586ba0) tests: Use portable IPv6 ping invocation.
- [a1067d40](https://github.com/ovn-org/ovn/commit/a1067d406184afdbd51381d1b9ed459200ff8fc0) debian: Source ovn-lib from ovn-host init script.
- [387e0391](https://github.com/ovn-org/ovn/commit/387e0391b7622d285484f4569f8bda7058796c3c) northd: Add missing ARP/ND flows for unreachable LB NATs.
- [ad7c9451](https://github.com/ovn-org/ovn/commit/ad7c945151c19af782b422ad2e51900ad89ab717) northd: Avoid useless iterations when recomputing policies.
- [5da68da2](https://github.com/ovn-org/ovn/commit/5da68da26347037b8b3aa64c8ce29b1baa44c4bd) northd: Avoid useless iterations when recomputing routes.
- [4fc8b97e](https://github.com/ovn-org/ovn/commit/4fc8b97eea5806b5eba27fb7c49261dc9208febe) tests: Fix dpctl related commands not properly executed at exit.
- [7ce18f8b](https://github.com/ovn-org/ovn/commit/7ce18f8b3458a8495cdc2f25bfcc8401a3f386ed) tests: Fix multiple dhcp tests related issues.
- [4cd2e271](https://github.com/ovn-org/ovn/commit/4cd2e2718768776de722b0283bea5ec5c9c715bb) tests: Fix load balancing system-tests.
- [a6d4e9fd](https://github.com/ovn-org/ovn/commit/a6d4e9fd8374b0feea21945c567b3c19bc6a7f58) tests: Start scapy at the beginning of the test.
- [163e5438](https://github.com/ovn-org/ovn/commit/163e54389405ee41d3cdc9e7721427c2f89fec3d) northd: Add missing feature change checks.
- [42835d03](https://github.com/ovn-org/ovn/commit/42835d034f570b9082f106c3308dc20b07736589) northd: Make sure we handle multicast group update.
- [cecb958f](https://github.com/ovn-org/ovn/commit/cecb958f6c926e89fbbade42fc6a490f6024d49b) northd: Fix 100% CPU when northd is paused.
- [6b5b0e72](https://github.com/ovn-org/ovn/commit/6b5b0e722b081508c3e81dd7f20993ebbb95b8f2) ovn-ic: Fix routes not deleted when lr is disabled.
- [534f4682](https://github.com/ovn-org/ovn/commit/534f4682fd9df0a7dedcc2a60563b056957f67c3) controller: Fix mac-cache race condition causing extra ARP.
- [1c85103a](https://github.com/ovn-org/ovn/commit/1c85103aa018feaf9cae92f9af8bc7c3a4256e60) Prepare for 25.09.5.