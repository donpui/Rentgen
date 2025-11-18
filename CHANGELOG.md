# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.0.6] - 2025-11-18

### Fixed

- Fix executable name build

### Note

💻 How to Run on macOS

macOS may block the app (“developer cannot be verified”).
To run it normally:

1. Move Rentgen.app to the Applications folder.
2. Open Terminal and run the following command:

`xattr -d com.apple.quarantine /Applications/Rentgen.app`

After this, you can launch Rentgen from Finder or Spotlight as usual.

## [1.2.0.5] - 2025-11-18

### Changed

- Added arm64 build for Windows and Linux

### Fixed

- Executable name

### Note

💻 How to Run on macOS

macOS may block the app (“developer cannot be verified”).
To run it normally:

1. Move Rentgen.app to the Applications folder.
2. Open Terminal and run the following command:

`xattr -d com.apple.quarantine /Applications/Rentgen.app`

After this, you can launch Rentgen from Finder or Spotlight as usual.

## [1.2.0.4] - 2025-11-18

### Fixed

- Fixed debian package build

## [1.2.0.3] - 2025-11-18

### Fixed

- Fixed release

## [1.2.0.2] - 2025-11-18

### Added

- Add Github actions for deployment

### Fixed

- Fixed [#10](https://github.com/LiudasJan/Rentgen/issues/10)

### Security

[Unreleased]: https://github.com/LiudasJan/Rentgen/compare/v1.2.0...HEAD
[1.2.0]: https://github.com/LiudasJan/Rentgen/releases/tag/v1.2.0
