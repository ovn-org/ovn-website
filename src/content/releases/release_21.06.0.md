+++
date = 2021-06-18T08:53:48-05:00
title = "Release 21.06.0"
+++

In addition to bug fixes, the 21.06.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- A new version of ovn-northd is included. This version is written in Differential Datalog instead of C and processes incrementally.
- VLAN passthru mode is supported.
- Custom 802.11ad support for localnet ports is added.
- An "allow-stateless" ACL option has been added that will always bypass conntrack.
- DNS now responds to PTR requests.
- There is now a "--dry-run" option for ovn-northd and ovn-northd-ddlog.

### Performance Enhancements
- The C version of ovn-northd can now process data in parallel threads.
- ct.inv can be disabled for deployments where offloading to smart NICs is desired.
- Similar to the ovn-nbctl daemon, ovn-sbctl has a daemon mode.

