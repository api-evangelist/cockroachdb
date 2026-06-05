# CockroachDB (cockroachdb)

CockroachDB is a distributed SQL database with strong consistency, PostgreSQL compatibility, and a managed cloud offering. The Cloud API manages cluster lifecycle; the Cluster API exposes per-node operational state for monitoring and troubleshooting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cluster Management
- Cloud
- Database
- Distributed SQL
- Infrastructure
- PostgreSQL Compatible
- SQL

## Timestamps

- **Created:** 2024-11-24
- **Modified:** 2026-05-19

## APIs

### CockroachDB Cloud API

REST API for managing the lifecycle of CockroachDB Cloud clusters. Supports cluster provisioning, scaling, deletion, SQL user management, network authorization (IP allowlists, private endpoints), customer-managed encryption keys (CMEK), maintenance windows, version deferral, audit log export, metric and log export, SCIM v2 group/user provisioning, folder organization, service accounts, API keys, invoices, and backup configuration. Authenticated via bearer tokens and rate-limited to 10 requests per second per user.

- **Human URL:** [https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)
- **Base URL:** `https://cockroachlabs.cloud`

#### Tags

- Cloud
- Cluster Management
- Database
- Infrastructure

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)
- [API Reference](https://www.cockroachlabs.com/docs/api/cloud/v1)
- [OpenAPI](openapi/cockroachdb-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cockroachdb-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cockroachdb-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CockroachDB Cluster API

REST API hosted by every CockroachDB node under the /api/v2 base path, exposed on the same HTTP port as the DB Console (default 8080). Provides health checks, node detail, hot range info, session and query introspection, database and table metadata, and event log retrieval. Authentication uses session tokens obtained via /api/v2/login/ and passed in the X-Cockroach-API-Session header.

- **Human URL:** [https://www.cockroachlabs.com/docs/stable/cluster-api](https://www.cockroachlabs.com/docs/stable/cluster-api)
- **Base URL:** `https://localhost:8080/api/v2`

#### Tags

- Cluster
- Database
- Monitoring
- Nodes
- Observability

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/stable/cluster-api)
- [API Reference](https://www.cockroachlabs.com/docs/api/cluster/v2)
- [OpenAPI](openapi/cockroachdb-cluster-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cockroachdb-cluster-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cockroachdb-cluster-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cockroach-labs)
- [JSON Schema](json-schema/cockroachdb-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cockroachdb-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cockroachdb-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Website](https://www.cockroachlabs.com/product/)
- [Documentation](https://www.cockroachlabs.com/docs/)
- [Pricing](https://www.cockroachlabs.com/pricing/)
- [Console](https://cockroachlabs.cloud/)
- [Git Hub](https://github.com/cockroachdb/cockroach)
- [Status Page](https://status.cockroachlabs.cloud/)
- [Features](undefined)
- [Integrations](https://www.cockroachlabs.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
