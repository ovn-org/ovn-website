+++
title = "Changelog v24.09.1"
[_build]
  list = 'never'
+++

### Changes from v24.09.0 to v24.09.1

- [972bedec](https://github.com/ovn-org/ovn/commit/972bedec0125478e2f39fb7e2d0752132f944879) Set release date for 24.09.1.
- [2a24b03f](https://github.com/ovn-org/ovn/commit/2a24b03f7f97068a0d3e87ecb77f139766d1df23) ipam: Do not report error for static assigned IPs.
- [1b8ac267](https://github.com/ovn-org/ovn/commit/1b8ac26784aed04bbd6f3ca32d87ca0ab91abc9c) ovn-trace: Fix copy-paste error for tracing put_nd_ra_opts().
- [222ee2a7](https://github.com/ovn-org/ovn/commit/222ee2a7ddf99fc3a833cc39625b32b2ccba91be) controller: Properly handle localnet flows in I+P.
- [3d3080d5](https://github.com/ovn-org/ovn/commit/3d3080d562106771230be22e9d76ce1aba55624a) binding: Fix race condition when claiming vif.
- [2679cd41](https://github.com/ovn-org/ovn/commit/2679cd4119a68673f90aeceb2153c5220a0eb738) controller: Accept unicast dhcp-discover in pinctrl_handle_put_dhcp_opts().
- [0611308a](https://github.com/ovn-org/ovn/commit/0611308a7a2e58911a18d974b1e8c7b2d8f0541f) ovn-ic: Fix potential segmentation violation.
- [809d4aac](https://github.com/ovn-org/ovn/commit/809d4aac64c4343f3bf845f2df497be2af6cba26) controller: Container lport install flows in MAIN chassis only.
- [2a60ba94](https://github.com/ovn-org/ovn/commit/2a60ba94f99486f1eb44134e693a8393059d4869) northd, controller: Use ct_next to get the CT state for direct SNAT.
- [4579cb66](https://github.com/ovn-org/ovn/commit/4579cb66599fedb433f8fc2fa0d9167e54feb457) ci: Pin scapy version.
- [7b006274](https://github.com/ovn-org/ovn/commit/7b00627433f3ee066cf6a5b727fec614c5e6eb77) northd: Respect --ecmp-symmetric-reply for single routes.
- [b3e47dc7](https://github.com/ovn-org/ovn/commit/b3e47dc70ad6bd2f92ffbe64a39ae4d98c0e8398) controller: Avoid quadratic complexity for multi-chassis ports.
- [8b3e276e](https://github.com/ovn-org/ovn/commit/8b3e276e228407068e0a9e72ad3e02969da2de1d) physical: Prevent wrong FDB to be learned with multichassis port.
- [8488c3c0](https://github.com/ovn-org/ovn/commit/8488c3c0aff73d1037a4af205ac3ba2ed22106a3) ovn-controller: Fix potential assert when exiting.
- [2282ae85](https://github.com/ovn-org/ovn/commit/2282ae8501faa5fe9bd607a5f0a81d863441f10f) Prepare for 24.09.1.