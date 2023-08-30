+++
title = "Changelog v23.06.1"
[_build]
  list = 'never'
+++

### Changes from v23.06.0 to v23.06.1

- [a20f880e](https://github.com/ovn-org/ovn/commit/a20f880efdba9dcf19c1df77b31a3b8b9dffa345) Set release date for 23.06.1.
- [d3488ea2](https://github.com/ovn-org/ovn/commit/d3488ea26e061c815402c0a0321d92a3dee7a847) northd, controller: Add CoPP for SVC monitor
- [6ee83671](https://github.com/ovn-org/ovn/commit/6ee83671e3f48899ef5be8c0315dcfd15bdb8c46) northd: Fix incorrect memory allocation for router group datapaths.
- [f0c257cd](https://github.com/ovn-org/ovn/commit/f0c257cdf1e2593b9ea140836a80d0b98127661f) northd: Fix recompute of referenced chassis in HA chassis groups.
- [938cc960](https://github.com/ovn-org/ovn/commit/938cc960050aadeea80214578dd08a2a98606781) ovn-nbctl: Prevent sync exiting early on nb_cfg overflow
- [4a4756fe](https://github.com/ovn-org/ovn/commit/4a4756fed1dd96505b6490946cb3acbe87b56fa5) tests: Add missing sync calls
- [0a5f296b](https://github.com/ovn-org/ovn/commit/0a5f296b5d724d082eb93e5483f131b48b83b031) tests: Make sure the port group is not hardcoded
- [cd10f6d9](https://github.com/ovn-org/ovn/commit/cd10f6d90e683ec13f6f6f2ce2d2bf11b6d983b5) system-tests: Make sure that the CT entries are sorted
- [5c15e012](https://github.com/ovn-org/ovn/commit/5c15e012751c11e4002c491d3325a3538b204f75) tests: Check proper DP and port key
- [3fcd201e](https://github.com/ovn-org/ovn/commit/3fcd201efc9ede6499efdcdbb67437e37b2338f8) NEWS: Add note about L4_SYM being used by default for ECMP.
- [1843e3aa](https://github.com/ovn-org/ovn/commit/1843e3aaa4f9b09327ec7b2a6043d964374f35d0) ovn-controller: Detect and use L4_SYM dp-hash if available.
- [bea8d473](https://github.com/ovn-org/ovn/commit/bea8d473c27f857531a2ba3c6b78acffda5ea1aa) fix missing documentation of ovn-ic arguments
- [cdcd80fa](https://github.com/ovn-org/ovn/commit/cdcd80fa6a749270bd034bfdaf89ad4dfc933e08) ovn-controller: Assume well-known tables are in the SB schema.
- [ae0c1480](https://github.com/ovn-org/ovn/commit/ae0c148078e4daccfb803929ddc14f862c6eaeff) tests: Change ct zone UUID->name migration test to use GW routers.
- [7794d6da](https://github.com/ovn-org/ovn/commit/7794d6daccb15f890c803456ffed957ca8e4a965) Fix a link.
- [add62b67](https://github.com/ovn-org/ovn/commit/add62b6779898299c4fc05504f34e728f423f68f) binding: handle ovs ofport update
- [fcce6664](https://github.com/ovn-org/ovn/commit/fcce66648bda465356fa7c54d05501c3584dc66f) system-tests: Wait for all interfaces to have IPv6
- [5e765dce](https://github.com/ovn-org/ovn/commit/5e765dce3bafc29cd0dbede1b557daf6dd038e28) tests: fixed "CT flush load balancer backends"
- [5df48df3](https://github.com/ovn-org/ovn/commit/5df48df362780ab101a82d500164549a555581b2) tests: fixed multiple ovn-ic unit tests
- [8da7fd00](https://github.com/ovn-org/ovn/commit/8da7fd0065502039c4cf5eef9cec857fd7a2a4d4) tests: fixed "Logical flows with Chassis_Template_Var reference"
- [3581c288](https://github.com/ovn-org/ovn/commit/3581c2887bffb0829e55879c32dd6219e45cdb97) controller: Migrate from ct zone UUID name to component name
- [1f0e0210](https://github.com/ovn-org/ovn/commit/1f0e021071a8a91b120e74faca99cfcc538ed45a) tests: fixed "ARP replies for SNAT external ips"
- [2551825c](https://github.com/ovn-org/ovn/commit/2551825c9c03bc9128a8b835be564bf83bcfe867) tests: fixed "ECMP IPv6 symmetric reply"
- [f76aebe2](https://github.com/ovn-org/ovn/commit/f76aebe25bd1014695c1a6a07fa3c5b90c451628) tests: increased bfd-mult to 15
- [ea0bf152](https://github.com/ovn-org/ovn/commit/ea0bf152d24705aeff8e6b2325e76d0344bbd9d1) tests: fixed another flake in "send gratuitous ARP for NAT rules on HA distributed router"
- [79635e4d](https://github.com/ovn-org/ovn/commit/79635e4deff1ae853873a0231545aa9ac4923819) ovn-controller: remove un-necessary "trying to release" warnings
- [8c8c1883](https://github.com/ovn-org/ovn/commit/8c8c18835dfa43eb6be7c6235fa93bb92082de4f) ovn-controller: avoid monitoring wrong chassis
- [789cf47c](https://github.com/ovn-org/ovn/commit/789cf47c2818ecc8a6d3062a3ffc89c01913dfd3) tests: run system tests also with monitor-all=true
- [0cbd64b5](https://github.com/ovn-org/ovn/commit/0cbd64b5b112d85098ea7a4aad3a8c35f5da7092) tests: fixed "Tiered ACLs"
- [243e2350](https://github.com/ovn-org/ovn/commit/243e23506ee167f051b6184f5ba2400115d6607f) tests: fixed "basic connectivity with multiple requested-chassis"
- [c647fed8](https://github.com/ovn-org/ovn/commit/c647fed8be75c39aded928102b47e1140381b2fa) tests: fixed flaky "4 HV, 3 LS, 2 LR, packet test with HA distributed router gateway port"
- [e92b0aba](https://github.com/ovn-org/ovn/commit/e92b0abab9c19173fc094b50b26dc87fa047fc53) tests: fixed "Mirror - remote" and "Mirror - local"
- [d2aaf1b1](https://github.com/ovn-org/ovn/commit/d2aaf1b131fa593dbf44c93d0136a900517b30e4) binding: fixed ovn-installed not properly removed (recomputes)
- [610d9fdf](https://github.com/ovn-org/ovn/commit/610d9fdf5aa5f7cd4752dc8beb2f42ef17523333) binding: fixed ovn-installed not properly removed (migration)
- [544504aa](https://github.com/ovn-org/ovn/commit/544504aa3318abbacad558c890b63a0bf0ee3481) tests: fixed typos in macro logs
- [139be79b](https://github.com/ovn-org/ovn/commit/139be79b07a850f9b458da7a0a6a752480d01f5d) ci: ovn-kubernetes: Figure out dependencies dynamically.
- [fa454b04](https://github.com/ovn-org/ovn/commit/fa454b046be90c9753a431b9e52b095655ec0603) ofctrl-seqno: Do not truncate the last acked value
- [c0158f3a](https://github.com/ovn-org/ovn/commit/c0158f3a17810673df2c120c01d510ba8d2f39df) binding: fixed qos when no iface
- [709d374b](https://github.com/ovn-org/ovn/commit/709d374b917e039d3668b4e6ab280d4c5cd3c4bd) qos: fix potential double deletion of ovs idl row
- [d95d1507](https://github.com/ovn-org/ovn/commit/d95d150758e1516a4ab34c15cd9428d214759580) tests: fixed userspace-system tests not properly cleaned up
- [d62049f2](https://github.com/ovn-org/ovn/commit/d62049f2a87239406f1852c9489baa8a86696971) pinctrl: Cap the max size of a prefix delegation DUID value.
- [4d4233e0](https://github.com/ovn-org/ovn/commit/4d4233e00a3a32bcd02c3667f95844fae544e49d) tests: Remove accidental debug echo.
- [2f5199cb](https://github.com/ovn-org/ovn/commit/2f5199cbfdd283f612558ae37c5bf1d4e536be2a) binding: fixed port claims as additional_chassis
- [e7969a47](https://github.com/ovn-org/ovn/commit/e7969a47f82a0022e02e503a4d38b44b01333dc8) tests: fixed "ovn-controller port security OF flows"
- [3a2dfd5b](https://github.com/ovn-org/ovn/commit/3a2dfd5b0e447254c62f32fabc7be43ca43bdb6e) system-tests: Do not hardcode DP key for the flows
- [a27ed93f](https://github.com/ovn-org/ovn/commit/a27ed93f9de6a344810301cffb7d581500036250) tests: fixed "MAC binding aging" and "IGMP external querier"
- [2b687771](https://github.com/ovn-org/ovn/commit/2b687771f8b029e4c950800f407047893f4b90eb) tests: fixed "ACL Reject ping pong"
- [6ac3b49e](https://github.com/ovn-org/ovn/commit/6ac3b49e7a79573a37afaace3815c5b47fb667f9) tests: fixed "nb_cfg timestamp"
- [5547749d](https://github.com/ovn-org/ovn/commit/5547749dc3fafe0071eea1c65a42bf1af9a65e70) tests: fixed "send gratuitous arp for nat ips in localnet"
- [a1e0cd31](https://github.com/ovn-org/ovn/commit/a1e0cd314b681f5dc5555b62cbe1d3a60c42c6d5) tests: fixed "check meters update"
- [29025f6c](https://github.com/ovn-org/ovn/commit/29025f6ce4623f2fa7253475c027ab136146cab8) tests: fixed "Encaps tunnel cleanup does not interfere with multiple controller on the same host"
- [9f3592ac](https://github.com/ovn-org/ovn/commit/9f3592ac6ea21429cb4ba0c717c15ef16e7a6817) tests: fixed "IPv6 periodic RA"
- [589f8d78](https://github.com/ovn-org/ovn/commit/589f8d78b6539da7dad5138303f853592daa3851) tests: decreased failure rate of "tug-of-war between two chassis for the same port"
- [96b748d4](https://github.com/ovn-org/ovn/commit/96b748d4e2035d7c465815c127497465aaf5fd90) tests: fixed "Load balancer health checks - IPv4 and IPv6"
- [2b431529](https://github.com/ovn-org/ovn/commit/2b431529b22fe6d8148f16613ce422c106dfc008) tests: fixed "send gratuitous ARP for NAT rules on HA distributed router"
- [695366c3](https://github.com/ovn-org/ovn/commit/695366c3bfe5a7ffd1167ad5956de0de8e71c936) tests: fixed "dhcpv6 : 1 HV, 2 LS, 5 LSPs" and "external logical port"
- [e863aec9](https://github.com/ovn-org/ovn/commit/e863aec96e4ff57f66f0ebc281da1608ec4b3d64) tests: fixed "policy-based routing" and "route tables IPv6 -- overlapping subnets"
- [e06f75bb](https://github.com/ovn-org/ovn/commit/e06f75bb876993e8e33f5ddb0066a0b984b1e296) mirror.c: Fix ovn-controller crash when mirror port is deleted from ovs.
- [d1595e5b](https://github.com/ovn-org/ovn/commit/d1595e5b3420c0731a100d088e2b842df15e95f4) call ovsrcu_exit() before exit in ovn-northd and ovn-controller to make valgrind happy
- [1b8c7f66](https://github.com/ovn-org/ovn/commit/1b8c7f6684c6feab3d223a32459752dae94aea98) controller: Turn OFTABLE_OUTPUT_INIT into an alias.
- [4af89ed6](https://github.com/ovn-org/ovn/commit/4af89ed6564ca18dd4ff73158560c36bfa38e49f) northd: Add logical flow to skip GARP with LLA
- [8dc2bc3a](https://github.com/ovn-org/ovn/commit/8dc2bc3a4f5dab7b00ed7a91af94a571f4708b2f) northd: match only on supported protocols to handle_svc_check
- [98edd6ea](https://github.com/ovn-org/ovn/commit/98edd6ea4fbc8908bb64c7c8eaeadb5ffd89a359) tests: Fixed "nested containers" test
- [eaf44337](https://github.com/ovn-org/ovn/commit/eaf443375c5312bcd01676baf20ee9852c15892d) tests: fix flaky Multiple OVS interfaces bound to same logical ports
- [2a6aaba0](https://github.com/ovn-org/ovn/commit/2a6aaba0746df3331a891fd92de3b85112aab642) system-tests: Prevent flakiness in ovn mirroring
- [2285a84c](https://github.com/ovn-org/ovn/commit/2285a84c4f19cdc19663dc4960c1a9590688de1b) system-tests: Prevent flakiness in Tiered ACLS
- [1eb8d03f](https://github.com/ovn-org/ovn/commit/1eb8d03fe1520468e5ab4bace07cd42407095f07) northd: Fix address set incremental processing
- [80364da1](https://github.com/ovn-org/ovn/commit/80364da1f842e64c13dc4403dfbc3192b27a6819) Prepare for 23.06.1.