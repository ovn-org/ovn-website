+++
date = 2022-12-14T16:02:35-05:00
title = "Release 22.12.0"
+++

22.12.0 is mainly a stability release. The vast majority of commits were made
with stabilization and fixing issues in mind.

In addition to bug fixes, the 21.12.0 release of OVN contains a mix of new
features and performance improvements.

### New Features
- There is a new option to automatically inherit load balancer groups from a
  logical router to its connected logical switches.
- A new load balancer affinity option has been added, which allows for a new
  load balancer backend to automatically be chosen after a configured time.
- IPFIX sampling has been added as a means of debugging dropped packets.
- A new logical flow action, ct\_commit\_nat, has been added, to allow for
  related packets (such as ICMP packets) to traverse a load balancer the same
  as the main connection traffic.
- Chassis template variables have been added to allow for easier configuration
  of similar load balancers that are applied across multiple chassis.

### Performance Enhancements
- Some additional incremental processing has been added to northd, including
  for address set and port group propagation from the northbound to the
  southbound database.
- Chassis template variables can be used to greatly reduce the number of
  logical flows that are created for load balancers, depending on the use case.
