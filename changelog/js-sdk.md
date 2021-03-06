# JavaScript SDK changelog

All notable changes to `zksync.js` will be documented in this file.

## Unreleased

### Added

### Changed

### Deprecated

- WebSocket provider.

### Fixed

## Version 0.8.4

### Added

- `updateTokenSet` function that updates the `tokenSet` stored in the `Provider`.
- `newMockProvider` and `DummyTransport`. Tests for the library.
- `closestGreaterOrEqPackableTransactionAmount` and `closestGreaterOrEqPackableTransactionFee` functions. Tests for
  them.
- Checks for ERC-1271 wallets for whether the messages should be prefixed

### Changed

- HTTP provider is now the default one.

### Fixed

- Bug with `integerToFloat` function. Now, it really rounds to the closest less or equal float number.

## Prior to 2020-12-10

**Version 0.8.3** is released.
