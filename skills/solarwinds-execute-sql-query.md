---
name: solarwinds-execute-sql-query
description: Execute a SWQL query against SolarWinds using the Query endpoint.
api: openapi/solarwinds-query-api-openapi.yml
operations:
- querySwis
- querySwisPost
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/solarwinds-query-api-openapi.yml ; every operationId checked against the contract
---

# solarwinds-execute-sql-query

Execute a SWQL query against SolarWinds using the Query endpoint.

## Steps

1. 1. Call `querySwis` (GET /Query) with the required query parameters as defined in the contract.
2. 2. Call `querySwisPost` (POST /Query) with the query in the request body as defined in the contract.

## Rules

- Use an authentication header appropriate to the chosen scheme (e.g., `X-Papertrail-Token` for apiToken, `Authorization: Bearer <token>` for bearerAuth, or basic auth).
- No rate‑limit is documented; exhaustion returns no specific HTTP status.
