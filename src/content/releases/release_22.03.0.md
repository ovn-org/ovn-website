+++
date = 2022-03-10T08:53:48-05:00
title = "Release 22.03.0"
+++

OVN 22.03.0 is a long term support (LTS) release. This version will receive bug fix support until the release of OVN 24.03.0, at which point it will receive one additional year of critical fixes.

In addition to bug fixes, the 22.03.0 release of OVN contains a mix of new features and performance improvements.

### New Features
- ovn-ic now supports multicast flooding between AZs.
- The --dummy-numa option for ovn-northd has been added.
- Control plan protection (CoPP) can now be named, allowing for easier referencing of policies.
- Solicited router advertisements now include rdnss, dnssl, and route\_info, just like periodic router advertisements.
- When ACL logging is enabled, the direction of the traffic is now included in the logs.
- A new "exclude-lb-vips-from-garp" option has been added so that if options:nat-addresses is set to "router" on a logical switch port, we will not send GARPs for load balancer VIPs on the connected logical router. 
- ACLs have a new log-related option that allows for reply and related traffic to be logged for stateful ACLs.
- from-lport ACLs can now optionally be applied after load balancing, in the case where an ACL might match on a load balancer backend.

### Performance Enhancements
- Incremental processing of address sets has been enhanced to be more fine-grained, resulting in fewer computations required when address sets are updated.
- Meters are now incrementally processed. This functions both as a bug fix as well as a performance enhancement.

### Documentation

Distribution documentation (aka man pages) specific to this release is
[available here](https://www.ovn.org/support/dist-docs-branch-21.09/).
