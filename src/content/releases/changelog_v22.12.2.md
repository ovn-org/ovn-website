+++
title = "Changelog v22.12.2"
[_build]
  list = 'never'
+++

### Changes from v22.12.1 to v22.12.2

- [daa3d8b9](https://github.com/ovn-org/ovn/commit/daa3d8b9d8225f1fdccc0297dce38ca8428f813b) Set release date for 22.12.2.
- [9045a780](https://github.com/ovn-org/ovn/commit/9045a7803c0bf47ac746c648498052456aa0b6f7) northd: check if parent_name is set for tag_request 0
- [6d5700d6](https://github.com/ovn-org/ovn/commit/6d5700d616107e617c40eb741df8bfa132b1cc4c) ofctrl: Prevent conjunction duplication
- [6b8d94b4](https://github.com/ovn-org/ovn/commit/6b8d94b4377f52d651b9b9a610451a505c7ae161) ofctrl: Do not try to program long flows
- [8ef0ee43](https://github.com/ovn-org/ovn/commit/8ef0ee43dc2af24dc419ce61b74bd65badf9e205) northd: Always ct commit ECMP symmetric traffic in the original direction.
- [427d60b7](https://github.com/ovn-org/ovn/commit/427d60b7946bea094427ad467cc6d901598a581c) Use correct nw_ttl=255 to match against legit NAs
- [8f06142d](https://github.com/ovn-org/ovn/commit/8f06142d6030b8791b1fc7310225669dcff55f9b) checkpatch: Ignore yml files when checking line lengths.
- [133761a5](https://github.com/ovn-org/ovn/commit/133761a5dbd6f0413cf27853df07190642d2ea39) northd: Make sure that skip_snat=true is evaluated before force_snat
- [08047a59](https://github.com/ovn-org/ovn/commit/08047a59f8a6d04f3d4741a9fdafd535358c5395) Prepare for 22.12.2.