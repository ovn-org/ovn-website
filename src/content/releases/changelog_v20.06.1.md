+++
title = "Changelog v20.06.1"
[_build]
  list = 'never'
+++

### Changes from v20.06.0 to v20.06.1

- [c4d0d513](https://github.com/ovn-org/ovn/commit/c4d0d51368fb9857ab9aa068cc6f7db369c6b3e3) Set release date for 20.06.1
- [7cc12230](https://github.com/ovn-org/ovn/commit/7cc12230f1322ca98f37d396d9bcc93864751597) ovn-northd: Fix memory leak in build_lswitch_rport_arp_req_flows().
- [4b1b9624](https://github.com/ovn-org/ovn/commit/4b1b9624901c1dc71d6f9c01e2038644e3545bae) ovn-controller: Fix the memory leak in ref lflow handling.
- [fc816ff6](https://github.com/ovn-org/ovn/commit/fc816ff6007d9c79f37771538088c171f45ab9b9) ovn-northd: Fix the missing lflow issue in LS_OUT_PRE_LB.
- [2640b73a](https://github.com/ovn-org/ovn/commit/2640b73ac7edb717331ff5256484a974d3473038) Fix selection fields for UDP and SCTP load balancers.
- [0db5cbf6](https://github.com/ovn-org/ovn/commit/0db5cbf65283fb41a7d28e5d0ad2f8ac14725d73) Split SB Port_Group per datapath.
- [bad3cc97](https://github.com/ovn-org/ovn/commit/bad3cc972ed18066335bdd0da0fbca922fff0601) chassis.c: Add comment to SB DB transaction only when needed.
- [b738f8b0](https://github.com/ovn-org/ovn/commit/b738f8b0aa648b118c63e627fd75c40332dcc27a) Cleanup `ovn-nbctl lr-route-add` IP normalization logic.
- [da7aab09](https://github.com/ovn-org/ovn/commit/da7aab095dc8c7ab34739a22001018de3fd2cad6) Use normalized IP addresses in `ovn-nbctl lr-nat-del`
- [0d624ca9](https://github.com/ovn-org/ovn/commit/0d624ca9e769b93650d11b9bf48caebb451a21f3) Use normalized IP addreses in `ovn-nbctl lr-nat-add`
- [9367c5b4](https://github.com/ovn-org/ovn/commit/9367c5b49c0cd9a8917e1966b093581ed90d0fb2) Add more IP address normalization functions.
- [ef097892](https://github.com/ovn-org/ovn/commit/ef097892a3a3c5ad24afad81d3a5730d0c1b127c) Use normalized IP addresses in `ovn-nbctl lrp-add`
- [7d19cc44](https://github.com/ovn-org/ovn/commit/7d19cc445e2956f75893c8ecd6b3b5380cb200de) Avoid case-sensitive MAC address comparisons.
- [427a8dcd](https://github.com/ovn-org/ovn/commit/427a8dcd2fe813cedd29b7248d3a97c4d2013c07) ovn-controller: Fix memleak in lflow_add_flows_for_datapath.
- [4982c713](https://github.com/ovn-org/ovn/commit/4982c7132c490f0cc65f147b72c85b1311948597) binding.c: Reorder out params of some of the static functions.
- [4dcc3065](https://github.com/ovn-org/ovn/commit/4dcc306581b7a2e108cf78b7c62d60e857e75019) Add an util function get_unique_lport_key() for generating unique lport key.
- [c573ae51](https://github.com/ovn-org/ovn/commit/c573ae51062b9a73e847b71e9fac7acb0faafdb8) tests: Enhance ovn-performance testing by adding gw router port.
- [a7c9df3c](https://github.com/ovn-org/ovn/commit/a7c9df3c478ef844bb711a936310809789aa0ddf) ovn-controller: Use the tracked runtime data changes for flow calculation.
- [3d096f83](https://github.com/ovn-org/ovn/commit/3d096f833c4a7d6f688a58c0d57629806936a926) ovn-controller: Handle runtime data changes in flow output engine
- [8bc8fe85](https://github.com/ovn-org/ovn/commit/8bc8fe85a5d51db21fa6aa183944c5a9d1189a12) ovn-controller: I-P for ct zone and OVS interface changes in flow output stage.
- [c7ed2c73](https://github.com/ovn-org/ovn/commit/c7ed2c73e3c986edbc10d5659fef39ad82d68bb3) I-P engine: Provide the option for an engine to clear tracked engine data in every run.
- [80f50554](https://github.com/ovn-org/ovn/commit/80f50554f98eaef6d59fbbe390ab29327008b802) northd: set packet length in check_pkt_larger()
- [aaf198b7](https://github.com/ovn-org/ovn/commit/aaf198b7fd2a4c85d02cfdd6125b6d87308fb269) Honour router_preference for solicited RA
- [bb6bf963](https://github.com/ovn-org/ovn/commit/bb6bf9630b41e587db9fc05a46aede5c80ed5c3e) Fix ovn-controller generated packets from getting dropped for reject ACL action.
- [cc1ae396](https://github.com/ovn-org/ovn/commit/cc1ae396c6197daf8ac48b4eabe077dc72b65456) northd: By pass IPv6 Router Adv and Router Solicitation packets from ACL stages.
- [8242db78](https://github.com/ovn-org/ovn/commit/8242db7882584dae00fc8869e43ff7acd1139358) ovn-controller: Fix I-P for SB Port_Binding and OVS Interface.
- [fae8454f](https://github.com/ovn-org/ovn/commit/fae8454f3312738e3c592bf27f95f1aee2dbb7d1) Prepare for 20.06.1