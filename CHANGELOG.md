Changelog
=========

All notable changes to this project will be documented in this file.

Unreleased
----------

v0.2.0 - 2018-04-14
-------------------

### Added

- Two new buildfiles for Phing
- Added wp-cli to phar.mk

v0.1.0 - 2018-04-04
-------------------

### Added

- Simple `.gitignore` were created
- Distributable `.makerc.dist` were created
- New buildfiles added for Phing: apach2, composer and portainer

### Changed

- `jawira/defaults` is going to copy all the content from `./resources/defaults/` 
recursively
- The creation of phar files were extracted from `Makefile` to `resources/make/phar.mk`


v0.0.2 - 2018-02-28
-------------------

### Added

- Pugx Badges and gif animation in [README.md](./README.md)
- Added [GLPv3 LICENSE](./resources/defaults/LICENSE) 

### Changed

- Default files were moved to `./resources/defaults/` dir

v0.0.1 - 2018-02-26
-------------------

### Fixed

- A valid SPDX license was added to [composer.json](./composer.json)

v0.0.0 - 2018-02-25
-------------------

### Added

- First full working version
- Final Production files are located in ./resources/



<!---
Guiding Principles

    Changelogs are for humans, not machines.
    There should be an entry for every single version.
    The same types of changes should be grouped.
    Versions and sections should be linkable.
    The latest version comes first.
    The release date of each versions is displayed.
    Mention whether you follow Semantic Versioning.

Types of changes

    ### Added       for new features.
    ### Changed     for changes in existing functionality.
    ### Deprecated  for soon-to-be removed features.
    ### Removed     for now removed features.
    ### Fixed       for any bug fixes.
    ### Security    in case of vulnerabilities.
-->