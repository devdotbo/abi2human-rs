# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2025-01-06

### Added
- Initial release of abi2human
- Zero-dependency Ethereum ABI to human-readable converter
- Support for functions, events, constructors, receive, and fallback
- Multiple output formats: JSON array, raw text, compact JSON
- Batch processing for directories
- Stream processing via stdin/stdout
- Comprehensive test suite

### Features
- Convert single ABI files
- Convert entire directories with pattern matching
- Pipeline support for integration with other tools
- Multiple output format options
- Human-readable function and event signatures

[Unreleased]: https://github.com/yourusername/abi2human-rs/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/yourusername/abi2human-rs/releases/tag/v1.0.0