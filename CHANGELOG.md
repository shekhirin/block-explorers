# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.6](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.6) - 2024-04-15

### Other

- Etherscan cache is constantly invalidated ([#40](https://github.com/foundry-rs/block-explorers/issues/40))

## [0.2.5](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.5) - 2024-04-03

### Dependencies

- Bump alloy-core ([#39](https://github.com/foundry-rs/block-explorers/issues/39))

### Miscellaneous Tasks

- Release 0.2.5

## [0.2.4](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.4) - 2024-03-29

### Bug Fixes

- Avoid setting extension when writing source tree to disk ([#32](https://github.com/foundry-rs/block-explorers/issues/32))

### Dependencies

- [deps] Bump reqwest to 0.12 ([#37](https://github.com/foundry-rs/block-explorers/issues/37))

### Miscellaneous Tasks

- Release 0.2.4
- Remove unused imports ([#33](https://github.com/foundry-rs/block-explorers/issues/33))

### Other

- Chain_id param in etherscan query req ([#36](https://github.com/foundry-rs/block-explorers/issues/36))
- Add concurrency ([#34](https://github.com/foundry-rs/block-explorers/issues/34))

## [0.2.3](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.3) - 2024-01-31

### Dependencies

- Bump foundry-compilers 0.3 ([#30](https://github.com/foundry-rs/block-explorers/issues/30))

### Miscellaneous Tasks

- Release 0.2.3

## [0.2.2](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.2) - 2024-01-26

### Miscellaneous Tasks

- Release 0.2.2
- Include value in serde error ([#29](https://github.com/foundry-rs/block-explorers/issues/29))
- Add unreleased section to cliff.toml
- Fix cliff, update CHANGELOG

## [0.2.1](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.1) - 2024-01-18

### Features

- Add viaIR to VerifyContract ([#28](https://github.com/foundry-rs/block-explorers/issues/28))

### Miscellaneous Tasks

- Release 0.2.1

## [0.2.0](https://github.com/foundry-rs/block-explorers/releases/tag/v0.2.0) - 2024-01-10

### Bug Fixes

- Exclude

### Dependencies

- [deps] Bump compilers
- [deps] Bump alloys ([#27](https://github.com/foundry-rs/block-explorers/issues/27))

### Miscellaneous Tasks

- Release 0.2.0
- Exclude useless directories
- Update cliff link
- Add CHANGELOG.md scripts ([#26](https://github.com/foundry-rs/block-explorers/issues/26))

## [0.1.3](https://github.com/foundry-rs/block-explorers/releases/tag/v0.1.3) - 2024-01-05

### Bug Fixes

- Dont force trailing url slash ([#25](https://github.com/foundry-rs/block-explorers/issues/25))

### Miscellaneous Tasks

- Release 0.1.3

### Other

- Add `getcontractcreation` binding ([#24](https://github.com/foundry-rs/block-explorers/issues/24))
- Fix deserialization error resulting from Blockscout omitting "OptimizationRuns" field when optimization was not used ([#23](https://github.com/foundry-rs/block-explorers/issues/23))
- Fix deserialization failure when fetching contract source_code from blockscout ([#22](https://github.com/foundry-rs/block-explorers/issues/22))

## [0.1.2](https://github.com/foundry-rs/block-explorers/releases/tag/v0.1.2) - 2023-12-08

### Bug Fixes

- Sanitize all source entries ([#19](https://github.com/foundry-rs/block-explorers/issues/19))

### Miscellaneous Tasks

- 0.1.2 ([#20](https://github.com/foundry-rs/block-explorers/issues/20))

## [0.1.1](https://github.com/foundry-rs/block-explorers/releases/tag/v0.1.1) - 2023-11-23

### Dependencies

- Bump Alloy

### Miscellaneous Tasks

- Release 0.1.1
- [meta] Add CODEOWNERS

## [0.1.0](https://github.com/foundry-rs/block-explorers/releases/tag/v0.1.0) - 2023-11-15

### Bug Fixes

- Add licensing ([#4](https://github.com/foundry-rs/block-explorers/issues/4))
- [features] Remove ethers-solc for foundry-compilers ([#3](https://github.com/foundry-rs/block-explorers/issues/3))

### Dependencies

- Bump ethers ([#9](https://github.com/foundry-rs/block-explorers/issues/9))

### Documentation

- Add CHANGELOG.md

### Features

- Remove Ethers ([#14](https://github.com/foundry-rs/block-explorers/issues/14))
- Repo improvements ([#11](https://github.com/foundry-rs/block-explorers/issues/11))
- Alloy migration ([#2](https://github.com/foundry-rs/block-explorers/issues/2))
- [`CI`] Enable ci/cd ([#1](https://github.com/foundry-rs/block-explorers/issues/1))
- Repo init

### Miscellaneous Tasks

- [meta] Update configs ([#15](https://github.com/foundry-rs/block-explorers/issues/15))
- Remove RawAbi and LosslessAbi usage ([#12](https://github.com/foundry-rs/block-explorers/issues/12))
- Enable more lints ([#13](https://github.com/foundry-rs/block-explorers/issues/13))
- Remove default feats from openssl ([#7](https://github.com/foundry-rs/block-explorers/issues/7))
- Patch ethers to be in sync w/ foundry ([#6](https://github.com/foundry-rs/block-explorers/issues/6))
- Clippy ([#5](https://github.com/foundry-rs/block-explorers/issues/5))

### Other

- Update README.md

### Styling

- Update rustfmt config ([#16](https://github.com/foundry-rs/block-explorers/issues/16))

<!-- generated by git-cliff -->