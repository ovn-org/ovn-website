+++
title = "Changelog v23.03.2"
[_build]
  list = 'never'
+++

### Changes from v23.03.1 to v23.03.2

- [05d20a51](https://github.com/ovn-org/ovn/commit/05d20a51032d65b6eed0c499cbb56ddbde5c754d) Set release date for 23.03.2.
- [22556693](https://github.com/ovn-org/ovn/commit/22556693895e75bef262dbba48f5a5342be41822) northd: check if parent_name is set for tag_request 0
- [02d2cf03](https://github.com/ovn-org/ovn/commit/02d2cf035e278c873bb1c54bf22a08c15a68f566) ofctrl: Prevent conjunction duplication
- [a480ed99](https://github.com/ovn-org/ovn/commit/a480ed99dba6a9ab533a466d5755426f128639ed) ofctrl: Do not try to program long flows
- [724cac38](https://github.com/ovn-org/ovn/commit/724cac380ad21e6d58461ad6a656fa17985ceebf) northd: Always ct commit ECMP symmetric traffic in the original direction.
- [9dc56cf4](https://github.com/ovn-org/ovn/commit/9dc56cf445e8e7d0518fd71f4bcfd99add8bb536) Use correct nw_ttl=255 to match against legit NAs
- [681bc898](https://github.com/ovn-org/ovn/commit/681bc898d79b1c713f547e92176be0b87ac0f63b) checkpatch: Ignore yml files when checking line lengths.
- [ec2acfd4](https://github.com/ovn-org/ovn/commit/ec2acfd4ace75158770f2d417e125acd333ecb4e) northd: Make sure that skip_snat=true is evaluated before force_snat
- [bed973da](https://github.com/ovn-org/ovn/commit/bed973da0d44a6228598e173e8760000e437eebd) Prepare for 23.03.2.