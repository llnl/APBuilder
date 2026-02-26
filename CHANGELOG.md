# Atmospheric Profile Builder (APBuilder)
<!-- markdownlint-disable MD024 -->

## 1.1.0 - 2026-02-26

### Added

- Flag `--vertical-coordinate` or `-vc` to enable use of geopotential height, with geometric height as the default

### Changed

- Convert the geopotential heights to geometric heights
- Changed minimum elevation range for 2D to start at 0
- Minimum supported Python version is 3.12
- Upgraded dependencies

### Fixed

- GitHub Actions to deploy container image and pages on tag push

### Removed

- Support for Python <= 3.11 is removed

## 1.0.0 - 2025-10-13

### Added

- Initial version
