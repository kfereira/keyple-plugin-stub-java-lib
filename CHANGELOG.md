# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.1.0] - 2022-06-03
### Added
- "CHANGELOG.md" file (issue [eclipse/keyple#6]).
- CI: Forbid the publication of a version already released (issue [#7]).
- New way of mocking APDU responses for a `StubSmartCard` using a provider (issue [#10]).
### Upgraded
- "Keyple Util Library" to version `2.1.0` by removing the use of deprecated methods.

## [2.0.0] - 2021-10-06
This is the initial release.
It follows the extraction of Keyple 1.0 components contained in the `eclipse/keyple-java` repository to dedicated repositories.
It also brings many major API changes.

[unreleased]: https://github.com/eclipse/keyple-plugin-stub-java-lib/compare/2.1.0...HEAD
[2.1.0]: https://github.com/eclipse/keyple-plugin-stub-java-lib/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/eclipse/keyple-plugin-stub-java-lib/releases/tag/2.0.0

[#10]: https://github.com/eclipse/keyple-plugin-stub-java-lib/issues/10
[#7]: https://github.com/eclipse/keyple-plugin-stub-java-lib/issues/7

[eclipse/keyple#6]: https://github.com/eclipse/keyple/issues/6