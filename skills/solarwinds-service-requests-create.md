---
name: solarwinds-service-requests-create
description: Create a new service request after optionally reviewing existing ones.
api: openapi/solarwinds-service-requests-api-openapi.yml
operations:
- listServiceRequests
- createServiceRequest
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/solarwinds-service-requests-api-openapi.yml ; every operationId checked against the contract
---

# solarwinds-service-requests-create

Create a new service request after optionally reviewing existing ones.

## Steps

1. 1. Call `listServiceRequests` – no required query parameters; use the appropriate authentication header (e.g., `Authorization: Bearer <token>` or `X-Papertrail-Token: <apiKey>`).
2. 2. Call `createServiceRequest` – include the request body fields defined by the contract (e.g., `title`, `description`, `requester_id`, etc.) and the same authentication header.

## Rules

- Authentication: supply a valid auth header (Bearer token, Basic auth, or X-Papertrail-Token) as defined by the provider.
- Idempotency: `createServiceRequest` is not idempotent; avoid duplicate submissions.
- Pagination: `listServiceRequests` may paginate results; follow `page` and `per_page` parameters if present.
