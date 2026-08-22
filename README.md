# SolarWinds (solarwinds)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring, and observability.

**APIs.json:** [https://www.solarwinds.com/apis.json](https://www.solarwinds.com/apis.json)

## Scope

- **Type:** Index

## Tags

- Application Monitoring
- Database Monitoring
- Infrastructure
- IP Address Management
- IT Management
- ITSM
- Log Management
- Network Monitoring
- Observability

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### SolarWinds Orion API

RESTful API for managing and monitoring network devices, servers, and applications through the Orion Platform. Provides access to the SolarWinds Information Service (SWIS) using SWQL queries via REST endpoints.

- **Human URL:** [https://www.solarwinds.com/orion-platform](https://www.solarwinds.com/orion-platform)
- **Base URL:** `https://{orion-server}:17778/SolarWinds/InformationService/v3`

#### Tags

- Infrastructure Management
- Network Monitoring
- Orion
- SWIS

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api.htm)
- [OpenAPI](openapi/solarwinds-orion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api-authentication.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [API Reference](https://github.com/solarwinds/OrionSDK/wiki/REST)

### SolarWinds Service Desk API

API for IT service management, ticketing, and help desk operations. Provides CRUD access to incidents, service requests, changes, problems, releases, and asset management resources.

- **Human URL:** [https://www.solarwinds.com/service-desk](https://www.solarwinds.com/service-desk)
- **Base URL:** `https://{instance}.samanage.com/api`

#### Tags

- Help Desk
- ITSM
- Service Desk
- Ticketing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/swsd/content/swsd_documentation.htm)
- [API Reference](https://apidoc.samanage.com/)
- [Authentication](https://help.samanage.com/s/article/API-Authentication)
- [Getting Started](https://documentation.solarwinds.com/en/success_center/swsd/content/swsd_getting_started_guide.htm)
- [OpenAPI](openapi/solarwinds-service-desk-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Observability API

Cloud-native observability API for logs, metrics, and distributed tracing.

- **Human URL:** [https://www.solarwinds.com/solarwinds-observability](https://www.solarwinds.com/solarwinds-observability)
- **Base URL:** `https://api.na-01.cloud.solarwinds.com`

#### Tags

- APM
- Cloud
- Logs
- Metrics
- Monitoring
- Observability
- Tracing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/observability/default.htm#cshid=api-overview)
- [OpenAPI](https://api.na-01.cloud.solarwinds.com/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [API Reference](https://documentation.solarwinds.com/en/success_center/observability/content/api/api-swagger.htm)
- [Authentication](https://documentation.solarwinds.com/en/success_center/observability/content/system/api-tokens.htm)
- [SDK](https://github.com/solarwinds)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Database Performance Analyzer API

API for database monitoring and performance analysis.

- **Human URL:** [https://www.solarwinds.com/database-performance-analyzer](https://www.solarwinds.com/database-performance-analyzer)
- **Base URL:** `https://{dpa-server}:8124/iwc/api`

#### Tags

- Database
- Monitoring
- Performance
- SQL

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/dpa/content/dpa-integrate-api.htm)
- [Documentation](https://documentation.solarwinds.com/en/success_center/dpa/default.htm)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds NPM REST API

Network Performance Monitor REST API for network device monitoring.

- **Human URL:** [https://www.solarwinds.com/network-performance-monitor](https://www.solarwinds.com/network-performance-monitor)
- **Base URL:** `https://{npm-server}:17778/SolarWinds/InformationService/v3`

#### Tags

- Monitoring
- Network
- Performance
- SNMP

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/npm/content/core-npm-rest-api.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Web Help Desk API

REST API for creating, reading, updating, and deleting data in Web Help Desk including tickets, clients, assets, and locations.

- **Human URL:** [https://www.solarwinds.com/web-help-desk](https://www.solarwinds.com/web-help-desk)
- **Base URL:** `https://{whd-server}/helpdesk/WebObjects/Helpdesk.woa/ra`

#### Tags

- Asset Management
- Help Desk
- IT Support
- Ticketing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/whd/content/helpdeskprogrammingrestapi.htm)
- [Documentation](https://documentation.solarwinds.com/archive/pdf/whd/whdapiguide.pdf)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Pingdom API

API for website uptime monitoring, performance monitoring, and transaction checks enabling automated management of checks, contacts, and reporting. Uses Bearer Token authentication for secure API access.

- **Human URL:** [https://www.solarwinds.com/pingdom](https://www.solarwinds.com/pingdom)
- **Base URL:** `https://api.pingdom.com/api/3.1`

#### Tags

- Performance
- Synthetic Monitoring
- Uptime Monitoring
- Website Monitoring

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/pingdom/content/topics/the-pingdom-api.htm)
- [API Reference](https://docs.pingdom.com/api/)
- [Authentication](https://documentation.solarwinds.com/en/success_center/pingdom/content/shared/sw-unified-login.htm)
- [OpenAPI](openapi/solarwinds-pingdom-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Loggly API

RESTful API for cloud-based log management including event submission, event retrieval, search, and account management. Supports sending events over HTTP/S and retrieving log data via paginating event retrieval endpoints.

- **Human URL:** [https://www.solarwinds.com/loggly](https://www.solarwinds.com/loggly)
- **Base URL:** `https://{subdomain}.loggly.com/apiv2`

#### Tags

- Cloud
- Log Management
- Logging
- Search

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-overview.htm)
- [API Reference](https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-retrieving-data.htm)
- [Authentication](https://documentation.solarwinds.com/en/success_center/loggly/content/admin/token-based-api-authentication.htm)
- [Getting Started](https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-sending-data.htm)
- [OpenAPI](openapi/solarwinds-loggly-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds Papertrail API

HTTP API for cloud-based log management including searching logs, managing systems, groups, saved searches, and user accounts. Provides endpoints for log search, settings management, and system configuration via token-based authentication.

- **Human URL:** [https://www.solarwinds.com/papertrail](https://www.solarwinds.com/papertrail)
- **Base URL:** `https://papertrailapp.com/api/v1`

#### Tags

- Cloud
- Log Management
- Logging
- Search

#### Properties

- [Documentation](https://www.papertrail.com/help/http-api/)
- [API Reference](https://www.papertrail.com/help/settings-api/)
- [Documentation](https://documentation.solarwinds.com/en/success_center/papertrail/content/kb/how-it-works/search-api.htm)
- [OpenAPI](openapi/solarwinds-papertrail-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds IPAM API

API for IP address management providing CRUD operations for subnets, IP addresses, and DNS entries through the SolarWinds Information Service.

- **Human URL:** [https://www.solarwinds.com/ip-address-manager](https://www.solarwinds.com/ip-address-manager)
- **Base URL:** `https://{orion-server}:17778/SolarWinds/InformationService/v3`

#### Tags

- DHCP
- DNS
- IP Address Management
- IPAM
- Network

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/ipam/content/ipam_documentation.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds NCM API

API for network configuration management providing automation of configuration backups, change management, and compliance through the SolarWinds Information Service.

- **Human URL:** [https://www.solarwinds.com/network-configuration-manager](https://www.solarwinds.com/network-configuration-manager)
- **Base URL:** `https://{orion-server}:17778/SolarWinds/InformationService/v3`

#### Tags

- Automation
- Compliance
- Configuration Management
- Network Configuration

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/ncm/content/ncm_documentation.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds SAM API

Server and Application Monitor API for monitoring application health and performance using the API Poller feature and SolarWinds Information Service.

- **Human URL:** [https://www.solarwinds.com/server-application-monitor](https://www.solarwinds.com/server-application-monitor)
- **Base URL:** `https://{orion-server}:17778/SolarWinds/InformationService/v3`

#### Tags

- APM
- Application Monitoring
- Performance
- Server Monitoring

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/sam/content/sam_documentation.htm)
- [Documentation](https://documentation.solarwinds.com/en/success_center/sam/content/sam-api-poller-methods.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SolarWinds AppOptics API

REST API for application performance monitoring providing CRUD access to metrics, dashboards, alerts, and traces. Supports custom metrics submission and distributed tracing for cloud-native applications. Note: AppOptics reached End of Service Life on November 30, 2025.

- **Human URL:** [https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm](https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm)
- **Base URL:** `https://api.appoptics.com/v1`

#### Tags

- APM
- Deprecated
- Metrics
- Monitoring
- Tracing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm)
- [Postman Collection](collections/solarwinds-loggly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-loggly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-orion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-orion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-papertrail.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-papertrail.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-pingdom.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-pingdom.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/solarwinds-service-desk.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/solarwinds-service-desk.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.solarwinds.com)
- [Documentation](https://documentation.solarwinds.com)
- [Support](https://support.solarwinds.com)
- [Blog](https://www.solarwinds.com/blog)
- [GitHub Organization](https://github.com/solarwinds)
- [Status Page](https://status.solarwinds.com)
- [Privacy Policy](https://www.solarwinds.com/legal/privacy)
- [Terms of Service](https://www.solarwinds.com/legal/terms)
- [Login](https://customerportal.solarwinds.com)
- [Security](https://www.solarwinds.com/information-security)
- [X (Twitter)](https://twitter.com/solarwinds)
- [LinkedIn](https://www.linkedin.com/company/solarwinds)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [C L I](https://github.com/solarwinds/OrionSDK/tree/master/Samples/PowerShell)
- [JSON-LD](json-ld/solarwinds-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/solarwinds-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/solarwinds-alert-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](https://www.solarwinds.com)
- [Use Cases](https://www.solarwinds.com)
- [Integrations](https://www.solarwinds.com)
- [Agent Skill](https://github.com/solarwinds/gns3-skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
