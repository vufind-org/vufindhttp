# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## Next Release - TBD

### Added

- Nothing.

### Changed

- The minimum PHP version requirement has been raised to 8.1.

### Deprecated

- Nothing.

### Removed

- Nothing.

## Fixed

- Nothing.

## 3.2.0 - 2022-09-15

### Added

- Nothing.

### Changed

- The minimum PHP version requirement has been raised to 7.4.1.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Improved compatibility with PHP 8.1.

## 3.1.0 - 2020-07-01

### Added

- Support for the 'socks5_hostname' proxy type setting.

### Changed

- CURLOPT_FOLLOWLOCATION is no longer set by default when the proxy type is 'socks5'; it can still be set through the $defaults constructor parameter, if needed.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- A reference to Zend in an exception message has been changed to Laminas.

## 3.0.0 - 2020-01-27

### Added

- Nothing.

### Changed

- Replaced Zend dependencies with Laminas equivalents; do not upgrade to 3.x until your application has updated all other Zend dependencies to Laminas.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 2.3.0 - 2019-10-23

### Added

- Support for overriding the regular expression used to detect local (i.e. not-to-be-proxied) hosts.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 2.2.0 - 2018-05-23

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- PHP 5 support.

### Fixed

- Nothing.
