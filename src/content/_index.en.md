---
title: "OVN, Open Virtual Network"
---

# OVN 
## Open Virtual Network 

OVN (Open Virtual Network) is a series of daemons that translates virtual
network configuration into OpenFlow, and installs them into Open vSwitch.
It is licensed under the open source Apache 2 license.

OVN is provides a higher-layer abstraction then Open vSwitch, working with
logical routers and logical switches, rather than flows. OVN is intended to be
used by cloud management software (CMS). For details about the architecture of
OVN, see the ovn-architecture manpage. Some high-level features offered by OVN
include

* Distributed virtual routers
* Distributed logical switches
* Access Control Lists
* DHCP
* DNS server 

Like Open vSwitch, OVN is written in platform-independent C. OVN runs entirely
in userspace and therefore requires no kernel modules to be installed.

{{% notice info %}}
Until recently, OVN code lived within the Open vSwitch codebase. OVN has
recently been split into its own repo.
{{% /notice %}}

