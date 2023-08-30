+++
title = "Changelog v20.06.2"
[_build]
  list = 'never'
+++

### Changes from v20.06.1 to v20.06.2

- [7d2438d4](https://github.com/ovn-org/ovn/commit/7d2438d4c9726860acf19576328161a973ac5e63) Set release date for 20.06.2.
- [323fac52](https://github.com/ovn-org/ovn/commit/323fac52db2140d3b4b76d7d80911861c0e2fc22) northd: Fix the routing for external logical ports of bridged logical switches.
- [ff3e1172](https://github.com/ovn-org/ovn/commit/ff3e1172959e9e88076e2b597e1d50b6bc7af239) ovn-northd: Add ARP responder flows for SNAT entries.
- [cd31e32f](https://github.com/ovn-org/ovn/commit/cd31e32f028fa7a06a7faaeeace307c1086e25b4) Fix the test case "80. ovn -- 4 HV, 1 LS, 1 LR, packet test with HA distributed router gateway port"
- [ff60e20c](https://github.com/ovn-org/ovn/commit/ff60e20ce3e0233ff6e3e9b036013be49373402b) ovn-northd.c: Support optionally disabling neighbor learning from ARP request/NS.
- [caf1b2d2](https://github.com/ovn-org/ovn/commit/caf1b2d2757d489b7df7e48f2049132a645d9ae6) actions: Implement new actions lookup_arp_ip and lookup_nd_ip.
- [e527ac4b](https://github.com/ovn-org/ovn/commit/e527ac4b6b2bf6c560fd683b9e1b8b8d525fe036) ovn-northd: Support optionally avoid static neighbor flows in routers.
- [435ef4fd](https://github.com/ovn-org/ovn/commit/435ef4fd9fc211a2231cfefa9d8071030cba82f1) ovn-northd.c: Remove the use of the REGBIT_SKIP_LOOKUP_NEIGHBOR bit.
- [51977181](https://github.com/ovn-org/ovn/commit/519771815b95919fcec9f3f6f85778543107022a) ovn-northd.8.xml: Fix reg9 bits documentation.
- [a55e176a](https://github.com/ovn-org/ovn/commit/a55e176a4335ed3da3b4e808866c649df0e25444) actions: Rename xxx_lookup_mac to xxx_lookup_mac_bind.
- [7dd4e862](https://github.com/ovn-org/ovn/commit/7dd4e862b2d25e3aae2d332218c2cb4a77780762) tests: Fix get_arp/get_nd tests mac-binding table id.
- [d242a4af](https://github.com/ovn-org/ovn/commit/d242a4afccb23533e4df263a4ad4eba166c3b720) ovn-northd: Fix logical flows to limit ARP/NS broadcast domain.
- [dea2588c](https://github.com/ovn-org/ovn/commit/dea2588c189c679c3b8f1edbd284b15b462d239c) ovn-northd: Fix is_chassis_resident() match for DNAT.
- [d7c42d4d](https://github.com/ovn-org/ovn/commit/d7c42d4df470b9c5d836f0931f9ec32dee6be9e9) ovn-northd: Minimize number of ARP/NS responder flows for DNAT.
- [b5ab546c](https://github.com/ovn-org/ovn/commit/b5ab546c52266794c08fe30c1fe1bd2e29bb0a84) ovn-northd: Refactor NAT address parsing.
- [0bcf9599](https://github.com/ovn-org/ovn/commit/0bcf95990b6fc2307f02b68d006f593fee7f223b) ovn-northd: Refactor ARP/NS responder in router pipeline.
- [763b588b](https://github.com/ovn-org/ovn/commit/763b588b2bd4a03065e3150c069c225f281f0102) ovn-northd: Store ETH address of router inport in xreg0.
- [d6733e55](https://github.com/ovn-org/ovn/commit/d6733e5599efe6fa65049b898245b7e153ef51c2) ovn-northd: Document OVS register usage in logical flows.
- [adcfdd40](https://github.com/ovn-org/ovn/commit/adcfdd408ac6860f47157516b9ec7b32585f12ee) pinctrl: Avoid flushing of non-local IGMP_Groups.
- [29dcea70](https://github.com/ovn-org/ovn/commit/29dcea70d0aceef4f5aa2c6663fbc3570192008d) chassis: Propagate ovn-monitor-all external-id to Chassis:other_config.
- [a33e3e90](https://github.com/ovn-org/ovn/commit/a33e3e90ea130674c118a66ba71779351a330981) ovn-controller: Release lport if the ofport of the VIF is -1.
- [5a9b996e](https://github.com/ovn-org/ovn/commit/5a9b996e1301277229114eac789db43c9878b115) ovn-detrace: Support SSL remotes.
- [cb9176b1](https://github.com/ovn-org/ovn/commit/cb9176b14bd52dd907d808850a1a80463983d26d) ovn-detrace: Add support for multiple remotes.
- [c60f1aa3](https://github.com/ovn-org/ovn/commit/c60f1aa3c0cf48f7700b622b712dbfb7bcd99998) ovn-controller: Clear flows not associated with db rows in physical flow change handler.
- [3c446f02](https://github.com/ovn-org/ovn/commit/3c446f027e5b4c88ec9c477bc601573a6259bf3a) ovn-controller: Fix the missing flows when logical router port is added after its peer.
- [c9ced21e](https://github.com/ovn-org/ovn/commit/c9ced21e36a7e7ce0c2799dcab8a981cef14a846) ovn-controller: Fix the missing ct zone entries for container ports.
- [7d310d17](https://github.com/ovn-org/ovn/commit/7d310d1746e92d7791f516e9af2ce8ce8ff3ef07) ovn-controller: Fix the missing flows with monitor-all set to True
- [029276e7](https://github.com/ovn-org/ovn/commit/029276e755a4d15fb9cf637092237fd85fda528d) Prepare for 20.06.2