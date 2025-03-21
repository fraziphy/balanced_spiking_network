# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
<!-- Add upcoming changes here -->

## [1.1.1] - 2025-03-19

### Fixed
- Fixed a misspelling in [file name or description, if relevant].

## [1.1.0] - 2025-03-19

### Added
- New feature: Configurable threshold distribution in `generate_heterogeneous_thresholds` function
  - Users can now choose between 'uniform' and 'normal' distributions
  - Added distribution type parameter to the function in utilities.py
  - Updated network initialization in network.py to support the new distribution parameter
  - Modified CLI arguments in cli.py to expose distribution selection to users

### Changed
- Enhanced biological plausibility by enforcing V_th > V_r constraint across all generated thresholds
- Improved handling of zero standard deviation cases in threshold generation
- Updated setup.py for dynamic versioning

### Fixed
- Ensured backward compatibility with default uniform distribution

## [1.0.0-dev] - [Date of v1.0.0-dev release]

### Added
- Initial development release
- [List any specific features or changes introduced in this dev version]

## [1.0.0] - [Release date of v1.0.0]

- Initial stable release

[Unreleased]: https://github.com/fraziphy/balanced-spiking-network/compare/v1.1.1...HEAD
[1.1.1]: https://github.com/fraziphy/balanced-spiking-network/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/fraziphy/balanced-spiking-network/compare/v1.0.0...v1.1.0
[1.0.0-dev]: https://github.com/fraziphy/balanced-spiking-network/releases/tag/v1.0.0-dev
[1.0.0]: https://github.com/fraziphy/balanced-spiking-network/releases/tag/v1.0.0
