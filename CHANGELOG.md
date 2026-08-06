# Changelog

All notable changes to this project will be documented in this file.

## [3.0.0] - 2026-08-01

### Added
- 10-dimension composable parent profile system (3^10 ≈ 59,049 combinations)
- Diagnosis mode: reverse-analyze parent type from user descriptions
- 5 new scenarios: social/friends, digital/screens, health/habits, appearance, education choices
- Dimension-level behavior generation rules for all 10 scenarios
- Diagnosis report format with visual profile, similarity matching, and communication tips
- Mixed mode: combine dimensions from different reference types

### Changed
- Restructured from 8 fixed types to composable dimension system
- Output format now includes full dimension profile
- Simulation logic now uses dimension influence rules instead of type templates

### Removed
- Fixed type × scenario matrix (replaced by dimension influence rules)

## [2.0.0] - 2026-07-31

### Added
- 8 parent type profiles (Tiger, Hustle, Helicopter, Zen, Zombie, Controller, Democratic, Absent)
- User selection mechanism (explicit, inferred, default)
- Scenario × type cross-reference matrix (5 scenarios × 8 types)
- Hybrid mode rules for mixed type simulation

### Changed
- Expanded from single-type to multi-type framework
- Output format updated with parent type field

## [1.0.0] - 2026-07-30

### Added
- Initial release
- Basic scenario library (5 scenarios)
- Core values and behavioral patterns
- Classic quotes reference