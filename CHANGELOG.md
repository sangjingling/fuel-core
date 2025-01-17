# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

Description of the upcoming release here.

### Added

- Something new here 1
- Something new here 2

### Changed

- Something changed here 1
- Something changed here 2

#### Breaking
- [#1262](https://github.com/FuelLabs/fuel-core/pull/1262): The `ConsensusParameters` aggregates all configuration data related to the consensus. It contains many fields that are segregated by the usage. The API of some functions was affected to use lesser types instead the whole `ConsensusParameters`. It is a huge breaking change requiring repetitively monotonically updating all places that use the `ConsensusParameters`. But during updating, consider that maybe you can use lesser types. Usage of them may simplify signatures of methods and make them more user-friendly and transparent.
- [#1290](https://github.com/FuelLabs/fuel-core/pull/1290): Standardize CLI args to use `-` instead of `_`

### Fixed

- Some fix here 1
- Some fix here 2

#### Breaking
- Some breaking fix here 3
- Some breaking fix here 4
