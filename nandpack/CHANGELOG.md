# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.3] - 2024-08-28
### Added
- New option for `files add` command to map file names
- Support of directories in `files` sub command
- Recalculating checksum upon packing
### Fixed
- Fixed deprecated dependecies

## [0.2.2] - 2024-01-23
### Added
- Added archive edition commands (add, list, remove, ...)
### Changed
- Updated loader v1 and v2 with new revision that remove the need to format RELs
- Changed `print` calls and `verbose` global for the `logging` module
- Using the `if __name__ == "__main__"` for better module compatibility
- Moved function only used in `main` to `main`'s scope
- Improved documentation.
### Removed
- Removed `format` command, since it is no longer needed

## [0.2.1] - 2022-04-22
### Added
- Added option to change the player's name in the save file
- Added command "banner" to extract the banner from a save file
### Changed
- Changed filename to reflect which version of the loader is patched in
- Made version 2 the default
- Updated version 2 of the loader for a smaller and less intrusive variant.
### Fixed
- Updated REL loader v1 for improved compatibility with REL loader v2

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