+++
title = "Changelog v24.03.4"
[_build]
  list = 'never'
+++

### Changes from v24.03.3 to v24.03.4

- [af5e1ee4](https://github.com/ovn-org/ovn/commit/af5e1ee49c6f7179c2bedd8a5fc49048b7041f33) Set release date for 24.03.4.
- [348ebb7d](https://github.com/ovn-org/ovn/commit/348ebb7d11bf4447b23eb2322dbd8e8c6ef1b19b) ovs: Bump submodule to OVS v3.3.2.
- [3ed3f7d0](https://github.com/ovn-org/ovn/commit/3ed3f7d0de755903ec5c226a8cc1758ee1134c8c) ipam: Do not report error for static assigned IPs.
- [ebe86803](https://github.com/ovn-org/ovn/commit/ebe86803d04cd1931778ccb6d754d8e5f0593caa) ovn-trace: Fix copy-paste error for tracing put_nd_ra_opts().
- [bc147b74](https://github.com/ovn-org/ovn/commit/bc147b74b0610d7b9c24e2d2416a985dca0d8774) controller: Properly handle localnet flows in I+P.
- [ac994c86](https://github.com/ovn-org/ovn/commit/ac994c86b14d713d4895f0822bf069fc26a24ed6) controller: Accept unicast dhcp-discover in pinctrl_handle_put_dhcp_opts().
- [63ea76b3](https://github.com/ovn-org/ovn/commit/63ea76b3644b65b3640640ea7928a991c23e9835) ovn-ic: Fix potential segmentation violation.
- [76c02051](https://github.com/ovn-org/ovn/commit/76c0205161ee20f941bf76a9d4eaf4070f45ed83) controller: Container lport install flows in MAIN chassis only.
- [040f5117](https://github.com/ovn-org/ovn/commit/040f5117d861980f761f2c7424600b1e9e2847e8) northd, controller: Use ct_next to get the CT state for direct SNAT.
- [fb585a79](https://github.com/ovn-org/ovn/commit/fb585a795a564db1faf0fa59ba59a19ab7350b4a) ci: Pin scapy version.
- [d9943161](https://github.com/ovn-org/ovn/commit/d9943161a95c00d701c18bb62faa0138eaf3e353) northd: Respect --ecmp-symmetric-reply for single routes.
- [0f6f45d9](https://github.com/ovn-org/ovn/commit/0f6f45d9fbabff5b7774938f4214a1a8463b018a) controller: Avoid quadratic complexity for multi-chassis ports.
- [3c6791e4](https://github.com/ovn-org/ovn/commit/3c6791e43714b22335acbce0648be59ad4671d2b) physical: Prevent wrong FDB to be learned with multichassis port.
- [231d1ca6](https://github.com/ovn-org/ovn/commit/231d1ca684c5708ab6a6d70567134f3ed135b4d5) ovn-controller: Fix potential assert when exiting.
- [7195dcd1](https://github.com/ovn-org/ovn/commit/7195dcd1b280233a1d21d5c3c2b5484f7a2fb24f) Documentation: Add inclusive-language documentation.
- [3c3109c7](https://github.com/ovn-org/ovn/commit/3c3109c7870e29bfa3cab482e4d59af2da0c1dbc) tests: Skip "IPv6 switching - megaflow check" if scapy is not installed.
- [bc56bc6f](https://github.com/ovn-org/ovn/commit/bc56bc6f70202b9a0dcc27f8a4721e4cfe21edc7) Reply only for the multicast ND solicitations.
- [1b65173e](https://github.com/ovn-org/ovn/commit/1b65173ef13bc738783b9f68058773d4a2aa98bf) Prepare for 24.03.4.