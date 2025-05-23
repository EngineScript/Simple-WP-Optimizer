# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Enhanced GitHub Actions workflows for plugin testing

## [1.5.5] - 2025-05-21
### Added
- WordPress 6.8 compatibility
- WordPress Plugin Check workflow for code quality verification
- Automated GitHub issue creation for test failures

### Fixed
- Changed text domain from 'simple-wp-optimizer-enginescript' to 'Simple-WP-Optimizer' to comply with WordPress.org standards
- Updated all internationalization function calls with the correct text domain
- Added missing text domain parameter in translation functions
- Fixed issue template formatting for automated GitHub issue creation

### Improved
- Made the plugin fully compatible with the WordPress Plugin Check tool
- Enhanced plugin repo compatibility
- Improved documentation and code comments

## [1.5.4] - 2025-05-04
### Changed
- Updated plugin name to "EngineScript: Simple WP Optimization"
- Improved code documentation and security notes
- Aligned version numbers in plugin header and constant definition

## [1.5.3] - 2025-03-15
### Added
- Enhanced security implementation with detailed documentation
- Added PHPCS ignore comments with security explanations
- Improved validation for DNS prefetch domains

### Fixed
- Fixed potential security issues with escaped outputs
- Fixed DNS prefetch implementation for better performance

## [1.5.2] - 2025-01-20
### Added
- Added Jetpack Blaze disabling feature

### Changed
- Improved function documentation with security notes
- Enhanced settings page with better organization

## [1.5.1] - 2024-11-05
### Changed
- Updated WordPress compatibility to 6.5
- Improved code organization
- Enhanced settings validation

## [1.5.0] - 2024-09-10
### Added
- Added option to disable Jetpack advertisements and promotions
- Implemented settings link in plugins page

### Changed
- Refactored settings page rendering for better security
- Updated text domain for better translation support

## [1.4.1] - 2024-07-25
### Added
- Enhanced DNS prefetching with better security measures
- Added proper input validation for domain entries

### Fixed
- Fixed escaping in DNS prefetch output
- Improved error handling for invalid domains

## [1.4.0] - 2024-05-30
### Added
- Added DNS prefetching for common external domains
- Added textarea input for custom DNS prefetch domains
- Implemented domain validation and sanitization

### Changed
- Improved settings organization with grouped options
- Enhanced option descriptions

## [1.3.0] - 2024-03-15
### Added
- Option to disable classic theme styles (added in WordPress 6.1+)
- Improved header cleanup options

### Changed
- Enhanced security for settings page
- Better user capability checks

## [1.2.0] - 2023-12-10
### Added
- Option to remove recent comments widget inline CSS
- Option to remove shortlinks from WordPress header

### Changed
- Improved settings validation
- Better code organization

## [1.1.0] - 2023-09-05
### Added
- Option to remove WLW manifest
- Option to remove WordPress version from header
- Comprehensive settings page with checkboxes

### Changed
- Switched to WordPress Settings API
- Better organization of options

## [1.0.0] - 2023-06-01
### Added
- Initial release
- Option to disable WordPress emojis
- Option to remove jQuery Migrate
- Basic settings page
- Default options