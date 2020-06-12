# Change Log

All notable changes to the "salesforce-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## Unreleased

### Added

- `sysassnoteq` snippet for `System.assertNotEqual(expected, actual);`.

## [0.3.0] - 2020-06-12

### Added

- `formap` snippet to iterate over a map.
- `ter` snippet for a ternary statment.
- `setidsfromrecordlist` snippet to return a set of ids from an SObject record list.

### Changed

- `mapids` snippet prefix to `mapfromrecordlist`

### Fixed

- The snippet table (`ifnotnull` + `testmethod` were missing).

## [0.2.1] - 2020-05-29

### Fixed

- The Snippet table in the readme to show correct snippets.

## [0.2.0] - 2020-05-29

### Changed

- For some snippets the final tab will leave the cursor at the end of a new line instead of adding a new line. This prevents the new line needing to be removed when not needed. (`newobj`, ``sobjecttype, `sobjectfield`, `describefieldresult`, `mapids`).

### Removed

- Snippets already in salesforce extension pack (`if`, `else`, `while`, `do while`).

## [0.1.0] - 2020-05-28

### Added

- Apex Snippets.
