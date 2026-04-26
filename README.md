# CockroachDB (cockroachdb)

CockroachDB is a distributed, PostgreSQL-compatible SQL database built by Cockroach Labs. It scales horizontally, survives disk, machine, rack, and data-center failures, and provides ACID transactions across geographies. CockroachDB is offered as a fully managed service on cockroachlabs.cloud (Basic, Standard, Advanced plans) and as self-hosted software. Two REST APIs are available: the CockroachDB Cloud API for managing the lifecycle of cloud-hosted clusters, and the per-node CockroachDB Cluster API for cluster health, monitoring, and operational status.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-26

## APIs

### CockroachDB Cloud API
REST API for managing the lifecycle of CockroachDB Cloud clusters. Supports cluster provisioning, scaling, deletion, SQL user management, network authorization, CMEK, maintenance windows, version deferral, audit log export, metric and log export, SCIM v2 group/user provisioning, folder organization, service accounts, API keys, invoices, and backup configuration.

**Human URL:** [https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)

#### Tags

- Cloud, Cluster Management, Database, Infrastructure

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)
- [API Reference](https://www.cockroachlabs.com/docs/api/cloud/v1)
- [OpenAPI](openapi/cockroachdb-cloud-api-openapi.yml)

### CockroachDB Cluster API
REST API hosted by every CockroachDB node under the /api/v2 base path, exposed on the same HTTP port as the DB Console (default 8080). Provides health checks, node detail, hot range info, session and query introspection, database and table metadata, and event log retrieval.

**Human URL:** [https://www.cockroachlabs.com/docs/stable/cluster-api](https://www.cockroachlabs.com/docs/stable/cluster-api)

#### Tags

- Cluster, Database, Monitoring, Nodes, Observability

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/stable/cluster-api)
- [API Reference](https://www.cockroachlabs.com/docs/api/cluster/v2)
- [OpenAPI](openapi/cockroachdb-cluster-api-openapi.yml)

## Common Properties

- [Website](https://www.cockroachlabs.com/product/)
- [Documentation](https://www.cockroachlabs.com/docs/)
- [Pricing](https://www.cockroachlabs.com/pricing/)
- [Console](https://cockroachlabs.cloud/)
- [GitHub](https://github.com/cockroachdb/cockroach)
- [Status](https://status.cockroachlabs.cloud/)
- [JSON-LD Context](json-ld/cockroachdb-context.jsonld)
- [Cluster JSON Schema](json-schema/cockroachdb-cluster-schema.json)
- [Spectral Ruleset](rules/cockroachdb-rules.yml)
- [Naftiko Capabilities](capabilities/cockroachdb-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
