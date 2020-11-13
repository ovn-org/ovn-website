+++
date = 2020-07-09T08:53:23-04:00
title = "Release 20.09.0"
+++

In addition to numerous bug fixes, the 20.09.0 release of OVN contains a mix of new features and performance improvements.

### New Features

- Allow the lb\_force\_snat\_ip and dnat\_force\_snat\_ip options to take an IPv4 and IPv6 address pair. This may be needed for dual stack setups.
- DHCP now understands DHCPDECLINE
- External IP based NAT. This allows for a set of IPs to be used for SNAT instead of always SNATting to a single external IP address. It also allows for a range of IPs to be matched for DNATting.
- VXLAN support has been added for general-purpose tunneling. Previously VXLAN could only be used for ramp switches. Please see documentation for details about limitations VXLAN introduces as compared to GENEVE and STT.

### Performance Enhancements

- Avoid using conntrack in certain scenarios. Conntrack is known to introduce latency. The following scenarios have been optimized to not use conntrack:
	- When sending packets from a logical switch to logical router when a load balancer is used.
	- When sending packets through a logical switch with a load balancer when the destination IP is not the load balancer VIP.
- Avoid nb\_cfg notification flooding. This significantly lowers the amount of time it takes for a northbound change to sync to all hypervisors.
- Probes for unix sockets are now disabled by default. This prevents unnecessary connection checks between processes on the same system.
- The set of OpenFlow flows sent to OVS is now incrementally processed.
- Parsed expressions are now cached in ovn-controller, meaning less CPU time is spent re-parsing expressions.
- The number of flows created for stateful ACLs has been reduced by a factor of 2 for allow-related ACLs and a factor of 3 for drop/reject ACLs.
