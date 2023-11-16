# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0]
### Uncategorized
- devDeps: remove unused ethjs-http-provider
- devDeps: chai@3.5.0->^4.3.10
- devDeps: mocha@3.2.0->^7.2.0
- devDeps: ethjs-provider-http@0.1.3->0.1.6
- npm dedupe; npm audit fix
- devDeps: async@^2.6.0->^2.6.4
- devDeps: cross-env@1.0.7->^6.0.3
- devDeps: pre-commit@1.1.3->^1.2.2
- devDeps: rimraf@2.3.4->^3.0.2
- chore: remove lint:staged script
- devDeps: remove unused check-es3-syntax-cli
- devDeps: remove unused ethereumjs-testrpc
- devDeps: remove unused eventsource-polyfill
- format CHANGELOG.md
- rename package from ethjs-contract to @metamask/ethjs-contract
- npm v5+ compat: rename prepublish script to prepare
- add package publishConfig
- chore: add .nvmrc set to v12
- deps: add missing promise-to-callback from devDeps ([#5](https://github.com/MetaMask/ethjs-contract/pull/5))
- ci: add GitHub Actions workflows
- Remove Travis and coveralls.io integrations
- devDeps: ganache-core@2.1.0 -> ganache-cli@^6.12.2
- Restrict compatible node versions to ^8.17 ([#2](https://github.com/MetaMask/ethjs-contract/pull/2))

## [0.1.6]
### Changed
- Bn formatting update

## [0.1.5]
### Removed
- Removed `ethjs-sha3` for `js-sha3`.

## [0.1.4]
### Fixed
- Fix object mutation with eth_call, eth_sendTransaction

## [0.1.3]
### Changed
- Webpack config updates
- Build config updates

## [0.1.2]
### Changed
- Updated ethjs-abi module
- More docs

## [0.1.1]
### Changed
- New Event object
- Package upgrades and fixes
- More docs

## [0.1.0]
### Changed
- promises, full coverage
  - Promises and callbacks on calls, new, event watchers
  - More coverage
  - Package upgrades

## [0.0.1]
### Added
- ethjs-contract
  - Basic testing
  - Basic docs
  - License

[Unreleased]: https://github.com/MetaMask/ethjs-contract/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.6...v0.3.0
[0.1.6]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.5...v0.1.6
[0.1.5]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/MetaMask/ethjs-contract/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/MetaMask/ethjs-contract/compare/v0.0.1...v0.1.0
[0.0.1]: https://github.com/MetaMask/ethjs-contract/releases/tag/v0.0.1
