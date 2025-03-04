# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.2] - 2023-02-23
### Added
- Added 3 second delay to Paytrail API callbacks to avoid race condition in cluster environments
- Company name field added to API calls when available

## [1.3.1] - 2022-12-12
### Fixed
- Loosened comparisons on the condition related to tax calculations when taxes amount to zero

## [1.3.0] - 2022-12-08
### Added
- Add support for manual renewals of Subscriptions
### Fixed
- Fix an issue with rounding taxes for small amounts
- Fix calculation with zero taxes
### Changed
- The order->payment_complete now happens later than before

## [1.2.4] - 2022-10-26
### Fixed
- Fixed an issue with rounding taxes for small amounts

## [1.2.3] - 2022-09-05
### Added
- Make it possible to tweak paytrail order items via apply_filters
### Changed
- PHP-SDK version updated to 2.3
- Updated various libraries
### Fixed
- Fixed language selection issue
- Checkout page login text tweak

## [1.2.2] - 2022-08-25
### Added
- Added login and registration instructions for guest users, so they can save card details
### Changed
- Updated supported features
### Fixed
- Hide empty payment method categories

## [1.2.1] - 2022-06-28
### Fixed
- Fixed an issue which prevented deleting saved card

## [1.2.0] - 2022-06-14
### Changed
- Updated Paytrail PHP-SDK to 2.2 version
### Fixed
- Fixed Guzzle version conflict issues by adding cUrl as a fallback option

## [1.1.0] - 2022-06-02
### Changed
- Updated Paytrail PHP-SDK version
- Removed symphony packages & composer installers

## [1.0.9] - 2022-03-16
### Added
- Added direct link to WooCommerce logs from the settings page
### Changed
- Improvements to order status checking
- Better logging for status changes and references

## [1.0.8] - 2022-02-11
### Fixed
- Update payment method image url

## [1.0.7.2] - 2021-12-08
### Fixed
- Added missing migration interface file

## [1.0.7] - 2021-12-08
### Added
- Added token migration functionality for WooCommerce Subscriptions orders

## [1.0.6] - 2021-12-02
### Added
- Added token migration functionality and upgrade instructions from old Checkout Finland plugin

## [1.0.5] - 2021-11-25
### Fixed
- Reverted a code change that broke customizer options

## [1.0.4] - 2021-11-04
### Changed
- Updated lock files

## [1.0.3] - 2021-11-04
### Added
- Added wordpress.org assets

## [1.0.2] - 2021-11-03
### Added
- Added even more escapes to variables and options 

## [1.0.1] - 2021-11-02
### Changed
- Added more escapes to variables and options 
- Renamed some CSS classes to improve compatibility with the old Checkout Finland for WooCommerce plugin

## [1.0.0] - 2021-10-20
### Added
- All initial plugin functionalities.
