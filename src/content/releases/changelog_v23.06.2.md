+++
title = "Changelog v23.06.2"
[_build]
  list = 'never'
+++

### Changes from v23.06.1 to v23.06.2

- [4a72621e](https://github.com/ovn-org/ovn/commit/4a72621eca026705b0c185ed2c2938a98e8b57d3) Set release date for 23.06.2.
- [c869db90](https://github.com/ovn-org/ovn/commit/c869db90e2b18515caad8ad95555d989d3379e3f) northd: check if parent_name is set for tag_request 0
- [4281178a](https://github.com/ovn-org/ovn/commit/4281178a8882d0194ce8edf35018227ab20fa80e) ofctrl: Prevent conjunction duplication
- [f18bbbbc](https://github.com/ovn-org/ovn/commit/f18bbbbc1ec0110cde8146ea4e2b34b1ec488ba7) ofctrl: Do not try to program long flows
- [6de90ba4](https://github.com/ovn-org/ovn/commit/6de90ba4c43e1798a63167fd7f790126cf240e9c) northd: Always ct commit ECMP symmetric traffic in the original direction.
- [059d1337](https://github.com/ovn-org/ovn/commit/059d1337af1be97b8f89fcf65e2ba6c9ae217d76) Use correct nw_ttl=255 to match against legit NAs
- [18b9ca06](https://github.com/ovn-org/ovn/commit/18b9ca0630c537b142d6ac849a6a2092d4f5bc0f) checkpatch: Ignore yml files when checking line lengths.
- [04cf3fd8](https://github.com/ovn-org/ovn/commit/04cf3fd8c2de752ac6ca538f6570547a69dcaac3) northd: Make sure that skip_snat=true is evaluated before force_snat
- [c215b523](https://github.com/ovn-org/ovn/commit/c215b5237d46e7aa3b7e095f1e955db5b646e4eb) Prepare for 23.06.2.