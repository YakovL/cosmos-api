# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

<!-- SIMSALA --> <!-- DON'T DELETE, used for automatic changelog updates -->

## [0.1.8-beta.0] - 2020-05-21

### Code Improvements

- Updated several libraries including Ledger transportation @faboweb

## [0.1.7] - 2020-02-01

### Fixed

- Unknown errors were not bubbled up to the user @faboweb

## [0.1.6] - 2020-01-29

### Repository

- Updated transport dependencies @faboweb

## [0.1.5] - 2020-01-07

### Fixed

- reenable confirmLedgerAddress @faboweb

## [0.1.4] - 2019-12-07

### Added

- Handle outdated browser error @faboweb

### Fixed

- Show correct feature flag URL for HID support @faboweb

## [0.1.3] - 2019-12-04

### Changed

- Handle the case were the Ledger is already used by another tab @faboweb

## [0.1.2] - 2019-12-04

### Fixed

- Reduce requirement to app version 1.5.3 @faboweb

## [0.1.1] - 2019-12-04

### Fixed

- Removes webpack as it didn't work properly with lazy loading dependencies @faboweb

## [0.1.0] - 2019-12-04

### Changed

- [#13](https://github.com/cosmos/lunie/pull/13) Switched to WebHID on Windows and WebUSB on OSX/Linux @faboweb

## [0.0.7] - 2019-11-28

### Changed

- Support new Cosmos App v2 @faboweb

### Repository

- Updated ledger cosmos js dependency @faboweb


## [0.0.6] - 2019-10-07


### Repository

- Reduced size of library @williamchong007

### Fixed

- Fixed address confirmation @faboweb

## [0.0.4] - 2019-06-12

### Fixed

- Removed webusb due to lack of support @faboweb

## [0.0.3] - 2019-06-05

### Repository

- Simplified and unified repository (using webpack) @faboweb
- Migrated to cosmos ledger lib v2 @faboweb

## [0.0.2] - 2019-05-24

### Added

- Extracted the Ledger Cosmos App wrapper from Lunie into this repo @faboweb