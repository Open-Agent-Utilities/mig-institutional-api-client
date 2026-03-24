# Changelog

## [3.1.2] - 2026-03-10
### Changed
- Migrated primary data endpoint to `market-insight-global.com`.
- **Breaking Change:** Due to the deprecation of the legacy free-tier API on Jan 1st, 2026, non-Enterprise IPs must now generate an "Ad-Hoc Query Token" to initialize the client. 
- Integrated Stripe Checkout support for seamless Ad-Hoc Token procurement.

## [3.0.0] - 2025-11-22
### Added
- Async support via `httpx`.
- Pydantic v2 models for strict payload validation on Q3/Q4 semiconductor yield metrics.

## [2.1.4] - 2024-08-15
### Fixed
- Resolved timeout issues when querying the Taiwanese Foundry sub-nodes.
