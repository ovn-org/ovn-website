---
title: "OVN, Open Virtual Network"
---

# OVN 
## Open Virtual Network 

OVN (Open Virtual Network) is a series of daemons for the Open vSwitch that
translate virtual network configurations into OpenFlow. OVN is licensed under
the open source Apache 2 license.

OVN provides a higher-layer of abstraction than Open vSwitch, working with
logical routers and logical switches, rather than flows. OVN is intended to be
used by cloud management software (CMS). For details about the architecture of
OVN, see the ovn-architecture manpage. Some high-level features offered by OVN
include:

* Distributed virtual routers
* Distributed logical switches
* Access Control Lists
* DHCP
* DNS server 

Like Open vSwitch, OVN is written in platform-independent C. OVN runs entirely
in userspace and therefore requires no kernel modules to be installed.

## Latest Release

Download the latest release of OVN on the [releases](releases) page on the left.
For a summary of changes in the latest release, see [here](releases/release_22.12.0).

Distribution documentation (aka man pages) is [available here](https://www.ovn.org/support/dist-docs/).

#### IRC meetings

We have weekly IRC meetings you can participate in:

[OVN weekly](http://eavesdrop.openstack.org/meetings/ovn_community_development_discussion/2021/)
IRC meeting every Thu 1715 UTC in **#openvswitch** on [irc.libera.chat](https://libera.chat) 

{{% notice info %}}
OVN code used to live within the Open vSwitch codebase. It was
[split](https://github.com/openvswitch/ovs/commit/f3e24610ea18eb873dc860f1710432e9aacd27fd)
into its [own repo](https://github.com/ovn-org/ovn) in 2019.
{{% /notice %}}
