+++
title = "Changelog v25.09.2"
[_build]
  list = 'never'
+++

### Changes from v25.09.1 to v25.09.2

- [e3e05878](https://github.com/ovn-org/ovn/commit/e3e0587865d8f02d0a8f72de53b82e464c5029d8) Set release date for 25.09.2.
- [8a457095](https://github.com/ovn-org/ovn/commit/8a4570952e0d69238bab55929e8addc698296b85) ovs: Bump to include fix for non-existent rows in idl uuid lookup.
- [223ffad2](https://github.com/ovn-org/ovn/commit/223ffad2d5ce4ab156af11b4e30271b51f923043) controller: Prevent learning of static routes in BGP.
- [62bf9268](https://github.com/ovn-org/ovn/commit/62bf92688dd877fc210118a4987fda2df796ee6f) northd: Skip transient SB datapath IDL records.
- [1962ed9a](https://github.com/ovn-org/ovn/commit/1962ed9aca7800c541693f3621eed0fa0785b4b6) pinctrl: Make sure we can learn IGMP groups only on switches.
- [481e50c4](https://github.com/ovn-org/ovn/commit/481e50c4fe724f64eecab01a886beb50dad415bb) northd: Fix potential segfault when deleting port groups.
- [17f05029](https://github.com/ovn-org/ovn/commit/17f05029c6116e7e8d9a9cfbbfce6d771409a7c3) datapaths: Handle simultaneous "new" and "deleted" datapaths.
- [1fa36ec7](https://github.com/ovn-org/ovn/commit/1fa36ec73f05252db1a0877a960918e004fda07a) pinctrl: Fix Service_Monitor reported online very slowly.
- [8d766c0a](https://github.com/ovn-org/ovn/commit/8d766c0a1009fe5884b817dbd8a3bdb46e83964e) pinctrl: Fix Service_Monitor status change not updated.
- [bc723027](https://github.com/ovn-org/ovn/commit/bc723027f65f448e14b8cd2e122079a34d4c7dbf) pinctrl: Speed up Service_Monitor updates.
- [1bc572d0](https://github.com/ovn-org/ovn/commit/1bc572d06395b3b81f0b717f4f90723e943ebac7) pinctrl: Avoid waking-up pinctrl thread too often.
- [48bc2460](https://github.com/ovn-org/ovn/commit/48bc24603d2ded52a8371597cb38a7920faa2751) pinctrl: Fix wrong value in timer_wait_until().
- [7c9a6074](https://github.com/ovn-org/ovn/commit/7c9a6074033c580f62076d08e3329d85aa323e40) northd: Add back check for datapath hmap.
- [63db9d92](https://github.com/ovn-org/ovn/commit/63db9d92b76cf112df1bc595a0c3032352cc94bf) northd: Remove duplicate code error.
- [1ace3d4f](https://github.com/ovn-org/ovn/commit/1ace3d4fadc80c05192870854f8cd0676ef029c8) pinctrl: Use proper drop counter for FDB.
- [e8a3770b](https://github.com/ovn-org/ovn/commit/e8a3770b87fffa6d6c17a695782a34487dba8af4) northd: Delete learned routes when dynamic-routing is false.
- [458b3831](https://github.com/ovn-org/ovn/commit/458b38315186e6046f1b354602edc0f1c072add7) tests: Ensure all central components stop at the end of the test.
- [71e018c5](https://github.com/ovn-org/ovn/commit/71e018c5d7f287184beda070b9f2276db8f7fe1c) Prepare for 25.09.2.