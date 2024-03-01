+++
title = "Changelog v22.03.6"
[_build]
  list = 'never'
+++

### Changes from v22.03.5 to v22.03.6

- [f894e167](https://github.com/ovn-org/ovn/commit/f894e167aa1e7957694ec1d161f209ec0bf07879) Set release date for 22.03.6.
- [0ac5e327](https://github.com/ovn-org/ovn/commit/0ac5e327dff127b718eab47c65ee837a5236437a) pinctrl: dns: Ignore additional records.
- [7f63921c](https://github.com/ovn-org/ovn/commit/7f63921cec6720857938aee3583513b03845864d) ovn-ic: Fix global blacklist filter for IPv6 addresses.
- [dd6d78d4](https://github.com/ovn-org/ovn/commit/dd6d78d4a2143ecce186feb92a87fd4eff901079) Documentation: Fix broken links in ovn-sandbox.rst.
- [e2117a8d](https://github.com/ovn-org/ovn/commit/e2117a8d4b460667cdfadf2c933f653a5c535474) github: Update versions of action dependencies (Node.js 20).
- [aff94da5](https://github.com/ovn-org/ovn/commit/aff94da55f6f5804216c0979b6ac1f8e2bd40cd3) actions: Use random port selection for SNAT with external_port_range.
- [8396f007](https://github.com/ovn-org/ovn/commit/8396f00743cb00d3229edbff8104d8da73f81557) ovn-ic: Handle NB:name updates properly.
- [47d61c5e](https://github.com/ovn-org/ovn/commit/47d61c5e7bee9f7e295dc175ef9ab25d1f65745f) controller: fixed potential segfault when changing tunnel_key and deleting ls.
- [26242f10](https://github.com/ovn-org/ovn/commit/26242f10a355edaf2a047710fde672e3cc2d8ed7) northd: Use proper field for lookup_nd
- [3772a121](https://github.com/ovn-org/ovn/commit/3772a1211ab8e8737f0420191550d5b632be08e3) test: add dedicated test for garp-max-timeout
- [1912442b](https://github.com/ovn-org/ovn/commit/1912442ba4adf9719ed10f9e54f4455e9cd20426) treewide: Fix small memory leaks reported by static analysis
- [03b622f7](https://github.com/ovn-org/ovn/commit/03b622f747ac891d02eae3c7efefe9ad340f540e) ovs: Bump submodule to include IDL "spurious delete" fix.
- [8d4c56e3](https://github.com/ovn-org/ovn/commit/8d4c56e33bf43cbc8fd14bff5d7c596d28a74f78) Correct ethtype referencing incorrect values
- [06639f10](https://github.com/ovn-org/ovn/commit/06639f108a57a47d522167a5dcfbf3347db5f07c) northd: forward arp request to lrp snat on.
- [3728fbf7](https://github.com/ovn-org/ovn/commit/3728fbf708ab4a743f4c7117865d7d1cee9dcaef) controller: make garp_max_timeout configurable
- [8548abb3](https://github.com/ovn-org/ovn/commit/8548abb345f13c88b7541d232f5c6a9dfed40353) system-tests: Consolidate wait condition in CoPP test
- [72b82f87](https://github.com/ovn-org/ovn/commit/72b82f875a8f356fe0e73b8515f4b762c49113e6) pinctrl: Fix up comments about sending RST packets for healthcheck.
- [037b1dcc](https://github.com/ovn-org/ovn/commit/037b1dcc3708c207c46dbb7b0878130d28c02095) fmt_pkt: make sure scapy-server is started once
- [e6f1df67](https://github.com/ovn-org/ovn/commit/e6f1df67883e319325666c1953feeb28730e58c8) fmt_pkt: improve scapy-server logging
- [0eaacaac](https://github.com/ovn-org/ovn/commit/0eaacaac8e135e10dd92a35d83088b599a5e1879) fmt_pkt: use -S check to wait for scapy sock file
- [97bf3ca9](https://github.com/ovn-org/ovn/commit/97bf3ca92093ec0e47a79b3f9cb632e2f11e3784) fmt_pkt: don't subshell when calling ovs-appctl
- [91d7cb79](https://github.com/ovn-org/ovn/commit/91d7cb7978b50ad0876961414d8884f1ca39c9b7) controller: fix group_table and meter_table allocation
- [3fb30fb8](https://github.com/ovn-org/ovn/commit/3fb30fb892855beffdbaf3338c36138cff0eec30) Prepare for 22.03.6.