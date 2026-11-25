# Security Policy

This repository hosts pre-built release binaries for CacheSweeper, a small
macOS utility app. It has no server component and no issue tracker for
general bugs beyond what's needed here.

## Reporting a vulnerability

If you find a security issue in CacheSweeper (e.g. in how it handles file
deletion, simulator erasing, or anything else that could be exploited),
please open a GitHub issue on this repository describing the problem.
There's no bug bounty, just a request to report responsibly rather than
disclose publicly first.

## Scope

- This app only deletes contents of well-known, app-rebuildable cache
  folders (npm, browser/app caches, Xcode DerivedData, Trash) and, with
  explicit per-device confirmation, erases iOS Simulator devices.
- It does not access the network, collect data, or require elevated
  privileges beyond normal user-level file access.
