# Fraud Platform

Open-source local-first card-fraud platform for development, testing, and learning.

## Repositories

- `card-fraud-platform` - shared local infrastructure (PostgreSQL, MinIO, Redis, Redpanda)
- `card-fraud-rule-management` - rule authoring and governance API
- `card-fraud-rule-engine-auth` - AUTH decisioning runtime (critical path)
- `card-fraud-rule-engine-monitoring` - MONITORING decisioning runtime
- `card-fraud-transaction-management` - ingestion, query, analyst workflow APIs
- `card-fraud-intelligence-portal` - analyst UI
- `card-fraud-e2e-load-testing` - cross-service load and E2E validation
- `card-fraud-ops-analyst-agent` - analyst-assist workflows and automation

## Legacy Repository Status

- `card-fraud-rule-engine` is legacy and retained temporarily as historical reference.
- Active runtime development has moved to:
  - `card-fraud-rule-engine-auth`
  - `card-fraud-rule-engine-monitoring`

## Getting Started

1. Clone all active repositories side-by-side.
2. Start shared infra from `card-fraud-platform`.
3. Run services standalone or run consolidated local validation from `card-fraud-e2e-load-testing`.

## Notes

- This org is focused on local development and integration hardening.
- CI/CD and production hardening are next phases.
