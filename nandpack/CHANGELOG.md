# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2021-10-14
### Added
- Support for the version 2 of the REL loader
- The last save time of the file is now set to the build date

### Fixes
- Check for duplicate files

## [0.1.0] - 2021-10-10
### Added
- Inital official revision of the script
- New features:
  - Generation of hacked Wii save
  - Injection into existing Wii save
  - Patching of standalone `zeldaTp.dat`
  - Unpacking of a Wii save into its component files
  - Packing a valid folder into a Wii save
  - Extracting the metadata from a Wii save
  - Format a standalone REL module to be compatible with the loading script