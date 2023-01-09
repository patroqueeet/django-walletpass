# Changelog

## [Unreleased]

### Changed

- upgrade pyopenssl usage due to https://github.com/pyca/cryptography/issues/6456.

#### Migration

move WWDR cert to .pem format and adjust setting `APPLE_WWDRCA_PEM_PATH`. Ensure it's G4. Validate with https://pkpassvalidator.azurewebsites.net/

## [1.2] - 2020-03-25

### Added

- Support JWT auth in push notifications
