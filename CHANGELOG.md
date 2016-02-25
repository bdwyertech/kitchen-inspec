# Change Log

## [0.12.2](https://github.com/chef/kitchen-inspec/tree/0.12.2) (2016-02-22)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.12.1...0.12.2)

**Fixed bugs:**

- Load directory from single inspec directory [\#54](https://github.com/chef/kitchen-inspec/issues/54)
- update to latest runner interface in inspec [\#56](https://github.com/chef/kitchen-inspec/pull/56) ([chris-rock](https://github.com/chris-rock))

## [v0.12.1](https://github.com/chef/kitchen-inspec/tree/v0.12.1) (2016-02-22)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.12.0...v0.12.1)

**Implemented enhancements:**

- Support inspec dir in the test suite dir [\#55](https://github.com/chef/kitchen-inspec/pull/55) ([alexpop](https://github.com/alexpop))

## [v0.12.0](https://github.com/chef/kitchen-inspec/tree/v0.12.0) (2016-02-19)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.11.1...v0.12.0)

**Implemented enhancements:**

- move integration tests to top-level [\#50](https://github.com/chef/kitchen-inspec/pull/50) ([chris-rock](https://github.com/chris-rock))
- support embedded profiles, leave directory checking to inspec [\#49](https://github.com/chef/kitchen-inspec/pull/49) ([chris-rock](https://github.com/chris-rock))

**Fixed bugs:**

- Point test-kitchen to master in Gemfile [\#48](https://github.com/chef/kitchen-inspec/pull/48) ([jaym](https://github.com/jaym))

**Merged pull requests:**

- require latest inspec version [\#53](https://github.com/chef/kitchen-inspec/pull/53) ([chris-rock](https://github.com/chris-rock))
- 0.12.0 [\#52](https://github.com/chef/kitchen-inspec/pull/52) ([chris-rock](https://github.com/chris-rock))

## [v0.11.1](https://github.com/chef/kitchen-inspec/tree/v0.11.1) (2016-02-15)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.11.0...v0.11.1)

**Implemented enhancements:**

- work well with other testing frameworks in test-kitchen [\#40](https://github.com/chef/kitchen-inspec/pull/40) ([chris-rock](https://github.com/chris-rock))

**Fixed bugs:**

- bugfix: use the right container in combination with kitchen-dokken [\#43](https://github.com/chef/kitchen-inspec/pull/43) ([chris-rock](https://github.com/chris-rock))

**Merged pull requests:**

- 0.11.1 [\#47](https://github.com/chef/kitchen-inspec/pull/47) ([chris-rock](https://github.com/chris-rock))
- deduplicate Gemfiles [\#41](https://github.com/chef/kitchen-inspec/pull/41) ([srenatus](https://github.com/srenatus))

## [v0.11.0](https://github.com/chef/kitchen-inspec/tree/v0.11.0) (2016-02-08)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.10.1...v0.11.0)

**Implemented enhancements:**

- Add integration test with test-kitchen [\#33](https://github.com/chef/kitchen-inspec/pull/33) ([chris-rock](https://github.com/chris-rock))

**Closed issues:**

- Failures should be tagged with the instance they failed against [\#30](https://github.com/chef/kitchen-inspec/issues/30)
- kitchen verify has exit status 0 with failed examples [\#9](https://github.com/chef/kitchen-inspec/issues/9)

**Merged pull requests:**

- 0.11.0 [\#38](https://github.com/chef/kitchen-inspec/pull/38) ([chris-rock](https://github.com/chris-rock))

## [v0.10.1](https://github.com/chef/kitchen-inspec/tree/v0.10.1) (2016-01-15)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.10.0...v0.10.1)

**Closed issues:**

- Inspec does not gracefully allow transports other than winrm and ssh. [\#31](https://github.com/chef/kitchen-inspec/issues/31)
- Specify inspec output formats in .kitchen.yml [\#26](https://github.com/chef/kitchen-inspec/issues/26)

**Merged pull requests:**

- 0.10.1 [\#34](https://github.com/chef/kitchen-inspec/pull/34) ([chris-rock](https://github.com/chris-rock))
- Allow transports which are subclasses of the core ones. [\#32](https://github.com/chef/kitchen-inspec/pull/32) ([coderanger](https://github.com/coderanger))

## [v0.10.0](https://github.com/chef/kitchen-inspec/tree/v0.10.0) (2016-01-07)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.9.6...v0.10.0)

**Fixed bugs:**

- kitchen test destroys the instance with failing tests [\#16](https://github.com/chef/kitchen-inspec/issues/16)
- Pending messages are "inherited"/"propagated" down with several suites [\#15](https://github.com/chef/kitchen-inspec/issues/15)

**Merged pull requests:**

- Preparing the 0.10.0 release [\#29](https://github.com/chef/kitchen-inspec/pull/29) ([tyler-ball](https://github.com/tyler-ball))
- Make test-kitchen a dev dependency [\#28](https://github.com/chef/kitchen-inspec/pull/28) ([jaym](https://github.com/jaym))
- Specify inspec output format from kitchen.yml [\#27](https://github.com/chef/kitchen-inspec/pull/27) ([cheesesashimi](https://github.com/cheesesashimi))
- remove gem push restriction [\#24](https://github.com/chef/kitchen-inspec/pull/24) ([arlimus](https://github.com/arlimus))

## [v0.9.6](https://github.com/chef/kitchen-inspec/tree/v0.9.6) (2015-12-11)
[Full Changelog](https://github.com/chef/kitchen-inspec/compare/v0.9.0...v0.9.6)

**Implemented enhancements:**

- add changelog [\#18](https://github.com/chef/kitchen-inspec/pull/18) ([chris-rock](https://github.com/chris-rock))
- support test suite helpers [\#12](https://github.com/chef/kitchen-inspec/pull/12) ([schisamo](https://github.com/schisamo))
- Fix typo in README [\#8](https://github.com/chef/kitchen-inspec/pull/8) ([englishm](https://github.com/englishm))
- Gem [\#7](https://github.com/chef/kitchen-inspec/pull/7) ([chris-rock](https://github.com/chris-rock))

**Fixed bugs:**

- tests fail with inspec 0.9.5 [\#19](https://github.com/chef/kitchen-inspec/issues/19)
- Fix tests and activate linting for CI [\#20](https://github.com/chef/kitchen-inspec/pull/20) ([srenatus](https://github.com/srenatus))
- raise ActionFailed when inspec returns other than 0. [\#13](https://github.com/chef/kitchen-inspec/pull/13) ([sawanoboly](https://github.com/sawanoboly))

**Closed issues:**

- ReadMe 'example here' dead link / 404 [\#21](https://github.com/chef/kitchen-inspec/issues/21)

**Merged pull requests:**

- 0.9.6 [\#23](https://github.com/chef/kitchen-inspec/pull/23) ([arlimus](https://github.com/arlimus))
- fix readme [\#22](https://github.com/chef/kitchen-inspec/pull/22) ([srenatus](https://github.com/srenatus))

## [v0.9.0](https://github.com/chef/kitchen-inspec/tree/v0.9.0) (2015-11-03)
**Implemented enhancements:**

- Update README.md [\#6](https://github.com/chef/kitchen-inspec/pull/6) ([chris-rock](https://github.com/chris-rock))
- Support all Kitchen/SSH as Train/SSH tunables. [\#4](https://github.com/chef/kitchen-inspec/pull/4) ([fnichol](https://github.com/fnichol))
- use new inspec as gem source [\#3](https://github.com/chef/kitchen-inspec/pull/3) ([chris-rock](https://github.com/chris-rock))
- Rename + Update [\#2](https://github.com/chef/kitchen-inspec/pull/2) ([chris-rock](https://github.com/chris-rock))
- add usage instructions [\#1](https://github.com/chef/kitchen-inspec/pull/1) ([chris-rock](https://github.com/chris-rock))

**Fixed bugs:**

- Add WinRM support to Verifier \(pending full support in Train\). [\#5](https://github.com/chef/kitchen-inspec/pull/5) ([fnichol](https://github.com/fnichol))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*