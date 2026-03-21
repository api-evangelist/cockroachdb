# CockroachDB (cockroachdb)
CockroachDB is a distributed SQL database built for cloud-native applications, offering resilience, scalability, and PostgreSQL compatibility. Cockroach Labs provides developer APIs for managing cloud-hosted clusters and self-hosted deployments, enabling programmatic control over database infrastructure and operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cockroachdb/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Cloud, Database, Cluster Management, Infrastructure

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### CockroachDB Cloud API
The CockroachDB Cloud API is a REST interface that provides programmatic access to manage the lifecycle of clusters within a CockroachDB Cloud organization. It enables developers and operators to create, configure, scale, and delete CockroachDB Serverless and Dedicated clusters without using the web console. The API supports operations including cluster provisioning, node management, network authorization, customer-managed encryption keys, and export configurations. Authentication is handled via bearer tokens, and the API is rate-limited to 10 requests per second per user. It can also be accessed through the CockroachDB Cloud Terraform provider for infrastructure-as-code workflows.

**Human URL:** [https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)


#### Tags:

 - Cloud, Database, Cluster Management, Infrastructure

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/cockroachcloud/cloud-api)
- [Documentation](https://www.cockroachlabs.com/docs/api/cloud/v1.html)
- [OpenAPI](openapi/cockroachdb-cloud-api-openapi.yml)

### CockroachDB Cluster API
The CockroachDB Cluster API is a REST API hosted by all nodes of a CockroachDB cluster that provides information about the cluster, its nodes, and operational status. It is available on the same HTTP port used by the DB Console, defaulting to port 8080, and exposes endpoints under the /api/v2 base path. The API enables monitoring and troubleshooting workflows using any HTTP-capable tooling, covering endpoints for health checks, node details, sessions, ranges, and database metadata. Authentication requires requesting a session token via the /login endpoint and passing it with subsequent requests using the X-Cockroach-API-Session header.

**Human URL:** [https://www.cockroachlabs.com/docs/stable/cluster-api](https://www.cockroachlabs.com/docs/stable/cluster-api)


#### Tags:

 - Database, Cluster, Monitoring, Nodes

#### Properties

- [Documentation](https://www.cockroachlabs.com/docs/stable/cluster-api)
- [Documentation](https://www.cockroachlabs.com/docs/api/cluster/v2.html)
- [OpenAPI](openapi/cockroachdb-cluster-api-openapi.yml)

## Common Properties

- [Portal](https://www.cockroachlabs.com/docs/)
- [Documentation](https://www.cockroachlabs.com/docs/)
- [Website](https://www.cockroachlabs.com)
- [Blog](https://www.cockroachlabs.com/blog/)
- [Login](https://cockroachlabs.cloud/login)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
