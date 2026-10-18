## [1.0.1] - 2026-10-19

### Fixed

- Register the overlay through `ctx.slots.inject('shell.overlay')` so activation waits for the host
  slot instead of failing on a fresh boot.

### Verified

- `node scripts/check.mjs`: 13 checks green.

# Changelog

All notable changes to this project are documented in this file.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-10-19

### Added

- Middle-click closes a sidebar/dock tab by clicking the tab's existing close control.
- Prevents middle-click autoscroll while over a tab.
- Tabs without a close control are left untouched.

### Verified

- `node scripts/check.mjs`: 12 checks green.
