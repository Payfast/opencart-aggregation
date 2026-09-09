# Changelog

## [[v1.4.0]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.4.0)

### Added

- Checkout signature refresh endpoint that re-signs the Payfast form amount immediately before submission.
- Cart-to-order synchronisation so stored order totals always match the live cart at payment time.

### Changed

- Updated `buildPayArray` to use an explicit nullable type (`?array`) for full PHP 8.3 compatibility.
- Built Payfast item name and description from live cart products with pipe separators and documented field-length limits.
- Module version raised to 1.4.0 for OpenCart v4.1.0.3.

### Fixed

- Corrected stale Payfast payment amounts when cart contents change after Payfast is selected at checkout.
- Resolved signature mismatch errors caused by comma delimiters and void-status order resynchronisation traps on OpenCart 4.1+.
- Restored accurate checkout confirm totals after browser back-forward cache and tab refocus navigation.

## [[v1.3.1]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.3.1)

### Added

- Payfast Aggregation label adjustments.

## [[v1.3.0]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.3.0)

### Added

- Code quality improvements for better maintainability.
- Updated for OpenCart v4.1.0.3 and PHP 8.2.
- Payfast Aggregation Branding.

### Changed

- Upgraded the Payfast common library to version 1.4.0.

## [[v1.2.0]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.2.0)

### Changed

- Refined code quality for improved performance and maintainability.
- Upgraded the Payfast common library for enhanced functionality and compatibility.

### Fixed

- Corrected currency amount formatting passed to the gateway, ensuring accurate transaction processing.

## [[v1.1.0]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.1.0)

### Added

- Integration with the Payfast common library.

### Changed

- Updated for OpenCart v4.0.2.3.
- Code quality improvements.

## [[v1.0.1]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.0.1)

### Changed

- Updated for OpenCart v4.0.2.2.

## [[v1.0.0]](https://github.com/Payfast/opencart-aggregation/releases/tag/v1.0.0)

### Added

- Initial release.
