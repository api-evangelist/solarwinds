---
name: solarwinds-crud-entity
description: Create, read, update, and delete a Solarwinds SWIS entity.
api: openapi/solarwinds-crud-api-openapi.yml
operations:
- createEntity
- readEntity
- updateEntity
- deleteEntity
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/solarwinds-crud-api-openapi.yml ; every operationId checked against the contract
---

# solarwinds-crud-entity

Create, read, update, and delete a Solarwinds SWIS entity.

## Steps

1. 1. Call `createEntity` with the required body fields for the new entity.
2. 2. Call `readEntity` with the `entityUri` returned from the create step.
3. 3. Call `updateEntity` with the same `entityUri` and the fields to modify.
4. 4. Call `deleteEntity` with the `entityUri` to remove the entity.

## Rules

- Auth: Include a bearer token in the `Authorization` header (e.g., `Authorization: Bearer <token>`).
- Idempotency: `createEntity` and `updateEntity` are not idempotent; repeat calls may create duplicate resources.
- Rate limiting: No rate limit is defined; exhaustion returns no specific HTTP status.
