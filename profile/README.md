# Fraud Platform

Open-source local-first card-fraud platform for development, testing, and learning.

## Repositories

- `card-fraud-platform` - shared local infrastructure (PostgreSQL, MinIO, Redis, Redpanda)
- `card-fraud-rule-management` - rule authoring and governance API
- `card-fraud-rule-engine` - decisioning runtime
- `card-fraud-transaction-management` - ingestion, query, analyst workflow APIs
- `card-fraud-intelligence-portal` - analyst UI
- `card-fraud-e2e-load-testing` - cross-service load and E2E validation

## Getting Started

1. Clone all 6 repositories side-by-side.
2. Start shared infra from `card-fraud-platform`.
3. Run each service standalone or run consolidated local validation.

## Notes

- This org is currently focused on local development and integration hardening.
- CI/CD and production hardening are planned next phases.
