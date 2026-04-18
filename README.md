# SolarWinds (solarwinds)

A collection of APIs provided by SolarWinds for IT infrastructure management, monitoring, and observability.

**URL:** [Visit APIs.json URL](https://www.solarwinds.com/apis.json)

## Tags

Application Monitoring, Database Monitoring, Infrastructure, IP Address Management, IT Management, ITSM, Log Management, Network Monitoring, Observability

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### SolarWinds Orion API
RESTful API for managing and monitoring network devices, servers, and applications through the Orion Platform.

**Human URL:** [https://www.solarwinds.com/orion-platform](https://www.solarwinds.com/orion-platform)

#### Tags

Infrastructure Management, Network Monitoring, Orion, SWIS

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api.htm)
- [OpenAPI](openapi/solarwinds-orion-openapi.yml)
- [Authentication](https://documentation.solarwinds.com/en/success_center/orionplatform/content/core-swis-api-authentication.htm)
- [SDK](https://github.com/solarwinds/OrionSDK)

### SolarWinds Service Desk API
API for IT service management, ticketing, and help desk operations.

**Human URL:** [https://www.solarwinds.com/service-desk](https://www.solarwinds.com/service-desk)

#### Tags

Help Desk, ITSM, Service Desk, Ticketing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/swsd/content/swsd_documentation.htm)
- [OpenAPI](openapi/solarwinds-service-desk-openapi.yml)
- [APIReference](https://apidoc.samanage.com/)

### SolarWinds Observability API
Cloud-native observability API for logs, metrics, and distributed tracing.

**Human URL:** [https://www.solarwinds.com/solarwinds-observability](https://www.solarwinds.com/solarwinds-observability)

#### Tags

APM, Cloud, Logs, Metrics, Monitoring, Observability, Tracing

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/observability/default.htm#cshid=api-overview)
- [OpenAPI](https://api.na-01.cloud.solarwinds.com/v1/openapi.json)
- [SDK](https://github.com/solarwinds)

### SolarWinds Database Performance Analyzer API
API for database monitoring and performance analysis.

**Human URL:** [https://www.solarwinds.com/database-performance-analyzer](https://www.solarwinds.com/database-performance-analyzer)

#### Tags

Database, Monitoring, Performance, SQL

### SolarWinds NPM REST API
Network Performance Monitor REST API for network device monitoring.

**Human URL:** [https://www.solarwinds.com/network-performance-monitor](https://www.solarwinds.com/network-performance-monitor)

#### Tags

Monitoring, Network, Performance, SNMP

### SolarWinds Web Help Desk API
REST API for tickets, clients, assets, and locations in Web Help Desk.

**Human URL:** [https://www.solarwinds.com/web-help-desk](https://www.solarwinds.com/web-help-desk)

#### Tags

Asset Management, Help Desk, IT Support, Ticketing

### SolarWinds Pingdom API
API for website uptime monitoring, performance monitoring, and transaction checks.

**Human URL:** [https://www.solarwinds.com/pingdom](https://www.solarwinds.com/pingdom)

#### Tags

Performance, Synthetic Monitoring, Uptime Monitoring, Website Monitoring

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/pingdom/content/topics/the-pingdom-api.htm)
- [OpenAPI](openapi/solarwinds-pingdom-openapi.yml)
- [APIReference](https://docs.pingdom.com/api/)

### SolarWinds Loggly API
RESTful API for cloud-based log management including event submission, search, and retrieval.

**Human URL:** [https://www.solarwinds.com/loggly](https://www.solarwinds.com/loggly)

#### Tags

Cloud, Log Management, Logging, Search

#### Properties

- [Documentation](https://documentation.solarwinds.com/en/success_center/loggly/content/admin/api-overview.htm)
- [OpenAPI](openapi/solarwinds-loggly-openapi.yml)

### SolarWinds Papertrail API
HTTP API for cloud-based log management including log search, system management, and saved searches.

**Human URL:** [https://www.solarwinds.com/papertrail](https://www.solarwinds.com/papertrail)

#### Tags

Cloud, Log Management, Logging, Search

#### Properties

- [Documentation](https://www.papertrail.com/help/http-api/)
- [OpenAPI](openapi/solarwinds-papertrail-openapi.yml)

### SolarWinds IPAM API
API for IP address management through the SolarWinds Information Service.

**Human URL:** [https://www.solarwinds.com/ip-address-manager](https://www.solarwinds.com/ip-address-manager)

#### Tags

DHCP, DNS, IP Address Management, IPAM, Network

### SolarWinds NCM API
API for network configuration management and compliance.

**Human URL:** [https://www.solarwinds.com/network-configuration-manager](https://www.solarwinds.com/network-configuration-manager)

#### Tags

Automation, Compliance, Configuration Management, Network Configuration

### SolarWinds SAM API
Server and Application Monitor API for monitoring application health and performance.

**Human URL:** [https://www.solarwinds.com/server-application-monitor](https://www.solarwinds.com/server-application-monitor)

#### Tags

APM, Application Monitoring, Performance, Server Monitoring

### SolarWinds AppOptics API (Deprecated)
REST API for application performance monitoring. End of Service Life: November 30, 2025.

**Human URL:** [https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm](https://documentation.solarwinds.com/en/success_center/appoptics/content/kb/custom_metrics/api.htm)

#### Tags

APM, Deprecated, Metrics, Monitoring, Tracing

## Capabilities

### Shared Per-API Definitions (capabilities/shared/)

| File | API |
|------|-----|
| [orion.yaml](capabilities/shared/orion.yaml) | SolarWinds Orion Platform API |
| [service-desk.yaml](capabilities/shared/service-desk.yaml) | SolarWinds Service Desk API |
| [pingdom.yaml](capabilities/shared/pingdom.yaml) | SolarWinds Pingdom API |
| [loggly.yaml](capabilities/shared/loggly.yaml) | SolarWinds Loggly API |
| [papertrail.yaml](capabilities/shared/papertrail.yaml) | SolarWinds Papertrail API |

### Workflow Capabilities

| File | Workflow | APIs Combined |
|------|----------|---------------|
| [infrastructure-monitoring.yaml](capabilities/infrastructure-monitoring.yaml) | Infrastructure Monitoring | Orion + Pingdom |
| [log-management.yaml](capabilities/log-management.yaml) | Log Management | Loggly + Papertrail |
| [it-service-management.yaml](capabilities/it-service-management.yaml) | IT Service Management | Service Desk + Orion |

## Artifacts

### OpenAPI Specifications (openapi/)

- [solarwinds-orion-openapi.yml](openapi/solarwinds-orion-openapi.yml)
- [solarwinds-service-desk-openapi.yml](openapi/solarwinds-service-desk-openapi.yml)
- [solarwinds-pingdom-openapi.yml](openapi/solarwinds-pingdom-openapi.yml)
- [solarwinds-loggly-openapi.yml](openapi/solarwinds-loggly-openapi.yml)
- [solarwinds-papertrail-openapi.yml](openapi/solarwinds-papertrail-openapi.yml)

### Spectral Rules (rules/)

- [solarwinds-spectral-rules.yml](rules/solarwinds-spectral-rules.yml)

### JSON Schema (json-schema/)

- [solarwinds-node-schema.json](json-schema/solarwinds-node-schema.json)
- [solarwinds-alert-schema.json](json-schema/solarwinds-alert-schema.json)
- Plus 43 API-specific schema files

### JSON-LD (json-ld/)

- [solarwinds-context.jsonld](json-ld/solarwinds-context.jsonld)
- Plus 5 API-specific context files

### Examples (examples/)

- 42 example files covering all API schemas

### Vocabulary (vocabulary/)

- [solarwinds-vocabulary.yaml](vocabulary/solarwinds-vocabulary.yaml)

## Common Properties

- [Portal](https://www.solarwinds.com)
- [Documentation](https://documentation.solarwinds.com)
- [Support](https://support.solarwinds.com)
- [Blog](https://www.solarwinds.com/blog)
- [GitHub Organization](https://github.com/solarwinds)
- [SDK](https://github.com/solarwinds/OrionSDK)
- [Status](https://status.solarwinds.com)
- [X](https://twitter.com/solarwinds)
- [LinkedIn](https://www.linkedin.com/company/solarwinds)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
