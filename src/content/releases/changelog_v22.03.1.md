+++
title = "Changelog v22.03.1"
[_build]
  list = 'never'
+++

### Changes from v22.03.0 to v22.03.1

- [6d3af524](https://github.com/ovn-org/ovn/commit/6d3af5241168481880e829bb71f9a3c768db7a83) Set release date for 22.03.1.
- [c53f3393](https://github.com/ovn-org/ovn/commit/c53f339342dbc3f79a34787f153f81989bac9909) northd: Use ct_mark.blocked and ecmp_reply_port only when all chassis support it.
- [8ba4efdf](https://github.com/ovn-org/ovn/commit/8ba4efdf219b1e20ed190e16a6af37aa6bdf7a69) northd: ovn-controller: Use ct_mark.natted only when ct_lb_mark is used.
- [bab59d76](https://github.com/ovn-org/ovn/commit/bab59d76ea96fefac315c522b5ce40928947ce99) northd: Use ct_lb_mark only when all chassis support it.
- [cb2e5706](https://github.com/ovn-org/ovn/commit/cb2e57060e9d7c4d5d2902e3a61474278a0a4241) binding.c: Make sure that localport is removed from local datapath
- [4e9ecbc7](https://github.com/ovn-org/ovn/commit/4e9ecbc757419f7fdfdfb88b9c3643dc09f2b2b6) physical.c: Move localport remote output flow definition
- [d3fbeea8](https://github.com/ovn-org/ovn/commit/d3fbeea8516ea8654b847f0d916d4bbca650ca05) physical.c: Avoid NULL ptr deref in populate_remote_chassis_macs
- [d1e05296](https://github.com/ovn-org/ovn/commit/d1e05296516583e7ed779572729c54ca31fe6c92) Use ct_mark for masked access to make flows HW-offloading friendly.
- [4c509ced](https://github.com/ovn-org/ovn/commit/4c509ceda237963359a86ceaca645aaa0cf84338) ovn-controller: Handle SB_Global:options:northd_internal_version in I-P engine.
- [b2281b86](https://github.com/ovn-org/ovn/commit/b2281b863560b3841554dba4f5e0328ed406341d) ovn-northd: Improve the doc and tests for ecmp-symmetric-reply.
- [e6c50afa](https://github.com/ovn-org/ovn/commit/e6c50afa9f53068254b86844ec37f18cf121ff09) actions: Add stack push and pop actions.
- [be66dbb1](https://github.com/ovn-org/ovn/commit/be66dbb1baec84f0fd14353b65542d7279aeb6ca) actions: Add action ct_lb_mark.
- [d48ff8f7](https://github.com/ovn-org/ovn/commit/d48ff8f749efed273d9a08bfaeb22d0954d34b7d) ovn-sb.xml: Fix ct_lb documentation.
- [fc2cdb49](https://github.com/ovn-org/ovn/commit/fc2cdb499023676e8faf9e368746896166d29114) northd: fix stateless nat with allowed_ext_ips
- [7d6d67c8](https://github.com/ovn-org/ovn/commit/7d6d67c824accf8b07a1da0e11c0aa70e8f22431) ovn-controller: Consider zone 0 as a valid zone when restoring.
- [56a836ce](https://github.com/ovn-org/ovn/commit/56a836ce24271a19a0e17e5ac2f70b15e8c8dde9) ovn-controller: Set Port_Binding.up field only if the Southbound DB is aware of this field
- [f93e36c8](https://github.com/ovn-org/ovn/commit/f93e36c8e3a30acbbe21c8641b8a4d48289578f0) northd: Honor ct-snat-zone option for common case.
- [28d40c0a](https://github.com/ovn-org/ovn/commit/28d40c0a024227c9c845117087b7594723ff0ec7) northd: handle container lport type update
- [bfa80196](https://github.com/ovn-org/ovn/commit/bfa80196810b3c1306cdb00a032fcc7fb54ba025) northd: fix lflow grouping in build_lb_rules
- [fcbe70bb](https://github.com/ovn-org/ovn/commit/fcbe70bb7746f7ff7b6f6481a4446ebaf600b030) ovn-controller: Avoid recompute triggered by external_ids:ovn-installed update.
- [d41054fc](https://github.com/ovn-org/ovn/commit/d41054fcc4926e553139ef4ab13ae65c3f009fcb) docs: fix a typo in bandwidth column name
- [83d07fee](https://github.com/ovn-org/ovn/commit/83d07fee947183253ec95c448b39d62aa6001d7f) ci: ovn-kubernetes: Add missing socat package
- [fa7d86a8](https://github.com/ovn-org/ovn/commit/fa7d86a8ae43fa208ef9a3980af396c1feaec92f) utilities: ovn-trace: fix reject action crash
- [ecd073a4](https://github.com/ovn-org/ovn/commit/ecd073a49eaec04db7de729a087410477e5811bb) utilities: nbctl: do not report errors for stateless nat if --may-exist is provided
- [ff1e858c](https://github.com/ovn-org/ovn/commit/ff1e858c99779bdbd48fc4b0d0a1fb39bc9606b9) lflow: Add MAC bindings when new datapath is added to chassis
- [39034eea](https://github.com/ovn-org/ovn/commit/39034eea28cc4b8f79e6af3844fd0d1b7f680bd6) northd: fix nat-v6 with exempted_ext_ips configuration
- [4f3656a2](https://github.com/ovn-org/ovn/commit/4f3656a20c7756f8ab9a7acae5ec192d37c1bf45) northd: dynamically compute l2 hdr len for check_pkt_larger action
- [83c737e1](https://github.com/ovn-org/ovn/commit/83c737e1741b24a58e1df333532529c9afb117a5) binding.c: Clear Port_Binding's encap column when encap-ip is removed.
- [c7071900](https://github.com/ovn-org/ovn/commit/c7071900c55d20160e3f2f2241059a8e8dd6a107) northd: Mark most of the SB columns as write-changed-only.
- [3da85a66](https://github.com/ovn-org/ovn/commit/3da85a6660776548ddafaa9759b260b0dac38b4b) parallel-hmap: rewrite iterator using multivar helpers
- [985ef458](https://github.com/ovn-org/ovn/commit/985ef4580ac6558859e104bad6fd5e2a68af79f7) treewide: bump ovs and fix problematic loops
- [367051da](https://github.com/ovn-org/ovn/commit/367051dacab28dbe875aba9e1920b5693cf284c3) Get OVS branch updated to proper base version for upcoming changes.
- [bd0ee4c1](https://github.com/ovn-org/ovn/commit/bd0ee4c1103ca5eaf834e48093205cacddaadf31) ovn-northd: Add flow to use eth.src if nd.tll is 0 in put_nd() action.
- [65088824](https://github.com/ovn-org/ovn/commit/65088824dbca07dfdf3402d1775d3af76a304ef4) Stop sending garps when binding not bound to chassis
- [77ec310d](https://github.com/ovn-org/ovn/commit/77ec310dda51c78c1897011ba851612787fcc6c6) pinctrl.c: Send GARP only on chassis atached to l3gw
- [388446ff](https://github.com/ovn-org/ovn/commit/388446ff27650773716ebcbc332424b1bf82bad1) system-ovn: fix CoPP test failures
- [92cdada0](https://github.com/ovn-org/ovn/commit/92cdada0e150e937e19f52c98a0c6a6dba7a84e0) ofctrl.c: Check installed flow when merging tracked flow changes.
- [6410cb79](https://github.com/ovn-org/ovn/commit/6410cb7906121bf2ebec3698d53bcfcb580ca4f6) northd: avoid writing to IDL in parallel when using northd parallelization
- [55a0ab5d](https://github.com/ovn-org/ovn/commit/55a0ab5d2971daaf22e3d935f623bf7548a3df98) controller/pinctrl: avoid accessing invalid memory
- [be49d514](https://github.com/ovn-org/ovn/commit/be49d5145e10b1e4a525eed3b12d7ffb7818f2d1) northd: avoid snat on reply packets
- [655c3aa7](https://github.com/ovn-org/ovn/commit/655c3aa74d45791b0de5548c787ee24a147f2456) vtep: correctly bring vtep lport up in SBDB
- [a814b865](https://github.com/ovn-org/ovn/commit/a814b865fbec460c91f9b5037d936b9d518c7a2f) controller: properly remove qos policy meters
- [93e21802](https://github.com/ovn-org/ovn/commit/93e21802ac27ed29f2a4daf58a10912ebd581db5) tests: Make "check CoPP config" more reliable.
- [3b07a5db](https://github.com/ovn-org/ovn/commit/3b07a5db4abd921a87b6fdfb851cf27e6975b079) inc-proc-eng: Properly log recompute reason.
- [e62886ef](https://github.com/ovn-org/ovn/commit/e62886efda51adadd6c01c4e7ee0bbd97994216c) NEWS: Update the 22.03.0 release date.
- [135310ca](https://github.com/ovn-org/ovn/commit/135310cae98e84a637f13e99439566846debcb29) rhel: fix logrotate user config option
- [622d15d0](https://github.com/ovn-org/ovn/commit/622d15d078178e854027358d5130690edbe75a4c) northd: Properly warn for NAT on LR with multiple gw ports.
- [b3d273f7](https://github.com/ovn-org/ovn/commit/b3d273f73c4aa8d246e652f1fb505779d3828c5b) Prepare for 22.03.1.