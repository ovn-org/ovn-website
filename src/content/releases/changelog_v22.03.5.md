+++
title = "Changelog v22.03.5"
[_build]
  list = 'never'
+++

### Changes from v22.03.4 to v22.03.5

- [15144069](https://github.com/ovn-org/ovn/commit/15144069080c5807957ba5bbb4248252eb4e6065) Set release date for 22.03.5.
- [b04a873a](https://github.com/ovn-org/ovn/commit/b04a873a8fe6677f837cfbd087d31c702aa082ec) pinctrl: reset success and failures n_count regardless of svc state
- [dd5d976c](https://github.com/ovn-org/ovn/commit/dd5d976c001593c016a28e829ad6f26a4a271589) pinctrl: send RST instead of RST_ACK bit for lb hc
- [a1723096](https://github.com/ovn-org/ovn/commit/a1723096809445b9ddf16fb4f401f46112e424e4) controller: Don't artificially limit group and meter IDs to 16bit.
- [3e5f6ac6](https://github.com/ovn-org/ovn/commit/3e5f6ac668bee720e51fbd51bdb16e1997a16222) tests: fixed race_condition with max_prefix
- [b9a019fd](https://github.com/ovn-org/ovn/commit/b9a019fddd03d87b905e953f577c7421aa223724) tests: fixed "ovn-nbctl - daemon retry connection"
- [29d16433](https://github.com/ovn-org/ovn/commit/29d16433ef726f9987a911a936435295cdfca71b) tests: fixed system test "LR with SNAT fragmentation needed for external server".
- [37f19989](https://github.com/ovn-org/ovn/commit/37f199896db8d24d736ffc63d41c7d9a71879f03) ovn-ctl man: Add election timer config to manpage
- [29124322](https://github.com/ovn-org/ovn/commit/291243221b4d96649f06a596edd89c0a2b5c3afd) controller: have I+P assigning ct_zones for l3gateway ports
- [5c12a221](https://github.com/ovn-org/ovn/commit/5c12a221e3613c945781f85e27e82e8cce3574b6) tests: fixed another set of flaky ovn-ic tests
- [fd593b84](https://github.com/ovn-org/ovn/commit/fd593b844c0fc142cbddefceef92804bbbe9658f) tests: do not start backup-northd by default
- [c43ee0aa](https://github.com/ovn-org/ovn/commit/c43ee0aaab70430d4d15386356a61b8ef8f16cc2) ci: Pin Python, Fedora and Ubuntu runner versions.
- [579380d2](https://github.com/ovn-org/ovn/commit/579380d2f56b49409b1306df6f20d78665076500) ovs: Bump submodule to include E721 fixes.
- [ff833995](https://github.com/ovn-org/ovn/commit/ff833995bb7b78284ddecf96c73dfca0a3443071) tests: Remove broken "feature inactivity probe" test.
- [827ff007](https://github.com/ovn-org/ovn/commit/827ff007a254acb929d06772da42a2bd5c7b2a68) ovs: Bump submodule to use v3.0.5.
- [62cfae95](https://github.com/ovn-org/ovn/commit/62cfae95d1edee4cbc5b356bac054b3976e465db) py-requirements: Remove hacking dependency and use recent flake8.
- [0deaaa54](https://github.com/ovn-org/ovn/commit/0deaaa54f068c51b78e021dfbbf7a0ae37773155) controller, northd: Wait for cleanup before replying to exit
- [e47d7821](https://github.com/ovn-org/ovn/commit/e47d78218339070dbb003dc6e979153370f322ea) tests: Add missing check for scapy.
- [4e04d4de](https://github.com/ovn-org/ovn/commit/4e04d4de9207db963cfe94b4ea89e25beaa67f9e) system-tests: Make sure that IPv6 address is available right away
- [674690bb](https://github.com/ovn-org/ovn/commit/674690bb3533534de3ccb83e758202871aeda9d2) northd: Allow need frag to be SNATed
- [b30f7c94](https://github.com/ovn-org/ovn/commit/b30f7c948c7e3e5e74799d9f17f35ab81dcdb0b1) memory-trim: Fix timestamp overflow warning right after reboot.
- [33e8ade3](https://github.com/ovn-org/ovn/commit/33e8ade327e2a196f89f6b9ba3cf8a286d5ea2de) tests: fixed "send gratuitous ARP for NAT rules on HA distributed router"
- [6c180197](https://github.com/ovn-org/ovn/commit/6c18019749cee68a512c716df478e404f25f21e0) tests: move trim_zeros() to ovn-macros
- [6b4e6669](https://github.com/ovn-org/ovn/commit/6b4e666905315113b8d4d977a5f78590a3a0fa50) tests: fixed "L2 Drop and Allow ACL w/ Stateful ACL"
- [046895e5](https://github.com/ovn-org/ovn/commit/046895e5aaf579b88aaece1940d4b430ea34f16d) tests: fixed multiple tests missing ovn-nbctl "wait"
- [ded718f7](https://github.com/ovn-org/ovn/commit/ded718f706fc2668c1267d11e70af41a5068d23d) tests: fixed "Logical router policy packet marking"
- [ed2ca4a8](https://github.com/ovn-org/ovn/commit/ed2ca4a802c53a098baabed0198bf53577093efb) tests: fixed multiple ovn-ic tests
- [96f70d46](https://github.com/ovn-org/ovn/commit/96f70d46f2b47f2c3119f33fe73316e0164d4016) pinctrl: Reply with correct destination for ICMPv6 RA packets
- [bc8276be](https://github.com/ovn-org/ovn/commit/bc8276be3251e0f98510b06600767c4bbf9cb9f7) ovn-controller: Add monitor condition for FDB.
- [792742ef](https://github.com/ovn-org/ovn/commit/792742efb36cb64013519d7f13dc95da53697aa3) northd: Drop packets destined to router owned NAT IP for DGP.
- [74de34d9](https://github.com/ovn-org/ovn/commit/74de34d9062d8d1cd5600b8f2ae1abde73955968) Rename scapy-server into scapy-server.py
- [a6415493](https://github.com/ovn-org/ovn/commit/a64154932fe70d878250e7f13a4c176715de7fa2) Add ovnkube-identity binary to the ovn-kubernetes Dockerfile
- [e19dc335](https://github.com/ovn-org/ovn/commit/e19dc3352b73b513201543afb7dc5553d8ab47ce) tests: offload scapy transformations to a separate unixctl daemon
- [dce2409f](https://github.com/ovn-org/ovn/commit/dce2409f1161a4cd6ecd8829a7c31b3d42b53526) Prepare for 22.03.5.