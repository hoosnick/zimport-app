# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-10-10

### Added

- Complete refactoring with modular architecture
- Separation of concerns (UI, Service, Data Access layers)
- Comprehensive error handling with custom exception hierarchy
- Centralized configuration management
- Structured logging system
- Retry logic and connection pooling for HTTP connectors
- Plugin-based connector architecture
- Type hints throughout the codebase
- PyQt6-based modern UI with improved styling
- Progress tracking and detailed logging in UI
- GitHub Actions workflows for automated builds
- Semantic versioning support
- Version bumping automation script
- Build script for creating executables
- Comprehensive documentation

### Changed

- Restructured project layout with `src/` directory
- Migrated from flat structure to layered architecture
- Improved data models with validation
- Enhanced SQL connector with better error handling
- Refactored JOWI connector with pagination support
- Updated ALIPOS connector with improved parsing
- Modernized UI components with better UX

### Fixed

- Connection string handling in SQL connector
- Pagination issues in JOWI connector
- Error handling across all connectors
- Configuration persistence issues

## [0.1.0] - Initial Release

### Added

- Basic POS integration support
- JETCAFE SQL connector
- JOWI HTTP connector
- ALIPOS cookie-based connector
- IIKO connector placeholder
- PyQt6 UI
- Configuration management
- Data export to JSON
