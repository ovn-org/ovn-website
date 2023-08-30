+++
title = "Changelog v21.12.2"
[_build]
  list = 'never'
+++

### Changes from v21.12.1 to v21.12.2

- [effc3aa6](https://github.com/ovn-org/ovn/commit/effc3aa676c7bc2f204dda74410e05ea9c6fa9b4) Set release date for 21.12.2.
- [ad3b6566](https://github.com/ovn-org/ovn/commit/ad3b6566bccfb6bc2341fe215be6fb83748434fe) northd: Use ct_mark.blocked and ecmp_reply_port only when all chassis support it.
- [22f4cbb5](https://github.com/ovn-org/ovn/commit/22f4cbb55131a453d3e23c86c3613b948a9f835d) northd: ovn-controller: Use ct_mark.natted only when ct_lb_mark is used.
- [6069caef](https://github.com/ovn-org/ovn/commit/6069caef46a36e8c12b7fbc01f40841db5a17c4b) northd: Use ct_lb_mark only when all chassis support it.
- [31834973](https://github.com/ovn-org/ovn/commit/31834973214431fd658f9b2eb2102399afee2d3f) binding.c: Make sure that localport is removed from local datapath
- [832afe77](https://github.com/ovn-org/ovn/commit/832afe772d2585c14db86a640bb2dd55b9958bde) physical.c: Move localport remote output flow definition
- [885b8c17](https://github.com/ovn-org/ovn/commit/885b8c176af5305d035591b0f371220d45820a13) physical.c: Avoid NULL ptr deref in populate_remote_chassis_macs
- [07f6522a](https://github.com/ovn-org/ovn/commit/07f6522a4c98bc393b7495724d133485809143f3) Use ct_mark for masked access to make flows HW-offloading friendly.
- [00d4e7e7](https://github.com/ovn-org/ovn/commit/00d4e7e70bb07b461e3a1b0eb2c20e12b175e0b1) ovn-controller: Handle SB_Global:options:northd_internal_version in I-P engine.
- [18f016bd](https://github.com/ovn-org/ovn/commit/18f016bd7a203419adba4e1ee8753d93978a81be) ovn-northd: Improve the doc and tests for ecmp-symmetric-reply.
- [f282d8b0](https://github.com/ovn-org/ovn/commit/f282d8b0a4f1e587755b7214325669f626af8748) actions: Add stack push and pop actions.
- [c3a8af65](https://github.com/ovn-org/ovn/commit/c3a8af65541b8aefebe6ff0d140f7a49c29316dc) actions: Add action ct_lb_mark.
- [b4556e9f](https://github.com/ovn-org/ovn/commit/b4556e9f9db30290e4a2a65128e4c51dc2d07482) ovn-sb.xml: Fix ct_lb documentation.
- [93cee76c](https://github.com/ovn-org/ovn/commit/93cee76c74bc03a498dabee5d853e572a70c6d41) northd: fix stateless nat with allowed_ext_ips
- [311c19ee](https://github.com/ovn-org/ovn/commit/311c19ee758dc3e7778ed233572703262ecd94fb) ovn-controller: Consider zone 0 as a valid zone when restoring.
- [f5d4d59e](https://github.com/ovn-org/ovn/commit/f5d4d59ed3488cc296e0b9b2a860ce28f99f5cb0) ovn-controller: Set Port_Binding.up field only if the Southbound DB is aware of this field
- [961f9a1a](https://github.com/ovn-org/ovn/commit/961f9a1afd08641ecdcbb874a5269d0834e067b8) northd: Honor ct-snat-zone option for common case.
- [5a72c9d0](https://github.com/ovn-org/ovn/commit/5a72c9d0512bed484e35af5c9f4a2efdf860001c) northd: handle container lport type update
- [f1c1c60e](https://github.com/ovn-org/ovn/commit/f1c1c60e27639dcbaef9dd27ae32be6bad04106d) northd: fix lflow grouping in build_lb_rules
- [716a7e48](https://github.com/ovn-org/ovn/commit/716a7e483bb143f1ff4b1bcddf16f79a05207a77) docs: fix a typo in bandwidth column name
- [8714282c](https://github.com/ovn-org/ovn/commit/8714282cce4c18ec1476b1d6b204289fd153955a) ci: ovn-kubernetes: Add missing socat package
- [7e9654c0](https://github.com/ovn-org/ovn/commit/7e9654c03fbb1ac820079afdd6e8d6292435225d) utilities: ovn-trace: fix reject action crash
- [1feca481](https://github.com/ovn-org/ovn/commit/1feca481e0113b2521ee343868b8c9d3af1b4fd0) utilities: nbctl: do not report errors for stateless nat if --may-exist is provided
- [a5f3fb89](https://github.com/ovn-org/ovn/commit/a5f3fb891cd255124581eab858cdd779d686e282) lflow: Add MAC bindings when new datapath is added to chassis
- [59fa1b99](https://github.com/ovn-org/ovn/commit/59fa1b99a6d1c42ed49a077f8be60041aae72a84) northd: fix nat-v6 with exempted_ext_ips configuration
- [5c185cfc](https://github.com/ovn-org/ovn/commit/5c185cfcf9c8fac03c42f1248f3e5e4caa74c77a) northd: dynamically compute l2 hdr len for check_pkt_larger action
- [30bc0f40](https://github.com/ovn-org/ovn/commit/30bc0f402ef89b5383c0a0a679df51206e488f64) ovn-northd: Add flow to use eth.src if nd.tll is 0 in put_nd() action.
- [4db73f09](https://github.com/ovn-org/ovn/commit/4db73f09c5a1a2abcc468dff9c65ecb7e716102e) ofctrl.c: Check installed flow when merging tracked flow changes.
- [e4530457](https://github.com/ovn-org/ovn/commit/e4530457b3935d9fda10fbf2d9352db921396b6c) northd: avoid writing to IDL in parallel when using northd parallelization
- [bb50b967](https://github.com/ovn-org/ovn/commit/bb50b967c1778cc6469761bb10b459bdb989f7e1) controller/pinctrl: avoid accessing invalid memory
- [4204ac1e](https://github.com/ovn-org/ovn/commit/4204ac1ef4b47540398a51d2db258c2d5533478d) vtep: correctly bring vtep lport up in SBDB
- [09d2f91c](https://github.com/ovn-org/ovn/commit/09d2f91c3579a9fa1ea2a57f7cab4a2489563248) controller: properly remove qos policy meters
- [19a0032b](https://github.com/ovn-org/ovn/commit/19a0032b60326e0c1be810d7d3a9b4cb55ebe069) ovs: Revert submodule after erroneous change.
- [05cd6245](https://github.com/ovn-org/ovn/commit/05cd6245db39baf750bd58d9eefd581ccf9c6418) acl-log: Log the direction (logical pipeline) of the matching ACL.
- [4d43d4fd](https://github.com/ovn-org/ovn/commit/4d43d4fdb9d5e515a9fe1d37e1620b32685a3c47) inc-proc-eng: Properly log recompute reason.
- [cbb8e71d](https://github.com/ovn-org/ovn/commit/cbb8e71dca93a9a0d2bcfb531fb234b04d0f2b58) rhel: fix logrotate user config option
- [f49d842f](https://github.com/ovn-org/ovn/commit/f49d842fc75f7a833157e70d97991ff7c6fb5307) northd: Properly warn for NAT on LR with multiple gw ports.
- [f091025b](https://github.com/ovn-org/ovn/commit/f091025ba3a38a0d9046214d046b9f09fdeb28e5) Prepare for 21.12.2.