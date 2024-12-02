+++
title = "Changelog v23.09.6"
[_build]
  list = 'never'
+++

### Changes from v23.09.5 to v23.09.6

- [ad065f1a](https://github.com/ovn-org/ovn/commit/ad065f1a8d80f137afc798a5091aed0ddc187d00) Set release date for 23.09.6.
- [79451641](https://github.com/ovn-org/ovn/commit/79451641570bc10e6434e3910620657791b674ac) ovs: Bump submodule to OVS v3.2.3.
- [883c3679](https://github.com/ovn-org/ovn/commit/883c3679cb9a09bafc3877aa62afba00b80cd67c) ipam: Do not report error for static assigned IPs.
- [44fe79b1](https://github.com/ovn-org/ovn/commit/44fe79b1ece10e3313d6a5809f4c2a36511bff61) ovn-trace: Fix copy-paste error for tracing put_nd_ra_opts().
- [d762c8fc](https://github.com/ovn-org/ovn/commit/d762c8fc9a3ae2e8bfb0fb0da865c41f0a338785) controller: Properly handle localnet flows in I+P.
- [b267acd6](https://github.com/ovn-org/ovn/commit/b267acd6f5f48e3a9f31277168c0a5c3798462e2) controller: Accept unicast dhcp-discover in pinctrl_handle_put_dhcp_opts().
- [13b2efae](https://github.com/ovn-org/ovn/commit/13b2efae615448a00fbef8f0db004ffc3f1ac6e0) ovn-ic: Fix potential segmentation violation.
- [d1f55ee8](https://github.com/ovn-org/ovn/commit/d1f55ee8158b6954deafab13e847004a455e8044) controller: Container lport install flows in MAIN chassis only.
- [d7738bdc](https://github.com/ovn-org/ovn/commit/d7738bdc2a08efca7199c55b9ea89e1a0a9c92ab) ci: Pin scapy version.
- [e2fa4a52](https://github.com/ovn-org/ovn/commit/e2fa4a52ccbc7b7af042d86de09708ed3573a099) northd: Respect --ecmp-symmetric-reply for single routes.
- [5c78002d](https://github.com/ovn-org/ovn/commit/5c78002d0f1fb2fc6e407c47a7c34beff3bf3149) controller: Avoid quadratic complexity for multi-chassis ports.
- [8e97c067](https://github.com/ovn-org/ovn/commit/8e97c06742cebac4c9bec1f95bda627aa468a2cb) northd: Fix NULL pointer deref within build_bfd_table.
- [db7c577e](https://github.com/ovn-org/ovn/commit/db7c577eca3ac0a030f4a9d626935cc2fc68da07) physical: Prevent wrong FDB to be learned with multichassis port.
- [fa8e36f5](https://github.com/ovn-org/ovn/commit/fa8e36f5a519b76642df1843aafb1c0852c2211b) ovn-controller: Fix potential assert when exiting.
- [ec2ade13](https://github.com/ovn-org/ovn/commit/ec2ade138a11f9438dcf8b2e47a98045b41b5585) Documentation: Add inclusive-language documentation.
- [caa6dc96](https://github.com/ovn-org/ovn/commit/caa6dc96d8addd7dfb89ff0def1f7c04e69beb50) tests: Skip "IPv6 switching - megaflow check" if scapy is not installed.
- [6b6bfd53](https://github.com/ovn-org/ovn/commit/6b6bfd53dd10fff1925c7f5b3658b689794c8ab9) Reply only for the multicast ND solicitations.
- [3b523c81](https://github.com/ovn-org/ovn/commit/3b523c8136099f46d8fe82ff2389d7ad733d77fc) Prepare for 23.09.6.