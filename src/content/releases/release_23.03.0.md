+++
date = 2023-03-03T16:02:35-05:00
title = "Release 23.03.0"
+++

In addition to bug fixes, the 23.03.0 release of OVN contains a mix of new
features and performance improvements.

### New Features
- Remote port mirroring support has been added as an experimental feature.
- Support for running multiple instances of ovn-controller on the same
  hypervisor has been added as an experimental feature.
- Load balancer health checks now also support IPv6.

### Performance Enhancement
- ovn-northd now uses bitmaps instead of hash tables for datapaths. This
  greatly reduces the lookup speed of datapaths and reduces memory usage
  as well.
- Unneeded calls to strlen have been replaced. Many of these were done as a
  means of ensuring the string was not zero-length. Now we just check the first
  byte of the string for the null character instead.
- When using IPFIX sampling, we now only sample if a collector set exists. This
  reduces unnecessary upcalls for cases where we are unable to actually sample.
