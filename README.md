# Nitric (nitric)

Nitric is an open-source cloud framework and infrastructure-from-code SDK plus CLI for building cloud applications in TypeScript, Python, Go, or Dart. You declare resources - APIs, schedules, queues, topics, buckets, key-value stores, secrets, and websockets - directly in your application code, and Nitric provisions them across AWS, Google Cloud, or Azure via pluggable Pulumi or Terraform providers. Nitric is a framework / IaC tool, not a hosted REST API - the APIs you build are deployed to your own cloud.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nitric/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nitric/refs/heads/main/apis.yml)

## Tags

- Infrastructure from Code
- Cloud Framework
- SDK
- CLI
- Serverless
- Multi-Cloud

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Nitric API Resource

SDK resource for declaring HTTP APIs and routes in code. Nitric provisions the API gateway (e.g. AWS API Gateway, GCP API Gateway, Azure API Management) and wires routes to your handlers. This is a framework primitive, not a hosted Nitric endpoint - the resulting API runs in your own cloud account.

- **Human URL:** [https://nitric.io/docs/apis](https://nitric.io/docs/apis)
- **Base URL:** `https://nitric.io/docs/apis`

#### Tags

- APIs
- HTTP
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/apis)
- [API Reference](https://nitric.io/docs/reference)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Schedule Resource

SDK resource for declaring time-based and cron schedules in code. Nitric provisions the underlying scheduler in your target cloud and triggers your handler on the defined cadence. Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/schedules](https://nitric.io/docs/schedules)
- **Base URL:** `https://nitric.io/docs/schedules`

#### Tags

- Schedules
- Cron
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/schedules)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Queue Resource

SDK resource for declaring durable message queues for batch and deferred processing. Nitric maps it to a cloud queue service (e.g. AWS SQS) with enqueue and dequeue semantics. Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/queues](https://nitric.io/docs/queues)
- **Base URL:** `https://nitric.io/docs/queues`

#### Tags

- Queues
- Messaging
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/queues)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Topic Resource

SDK resource for declaring publish/subscribe topics for event-driven architectures. Nitric provisions the cloud pub/sub service (e.g. AWS SNS, GCP Pub/Sub) and wires subscribers to handlers. Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/messaging](https://nitric.io/docs/messaging)
- **Base URL:** `https://nitric.io/docs/messaging`

#### Tags

- Topics
- Pub/Sub
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/messaging)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Bucket Resource

SDK resource for declaring object/file storage buckets with read, write, delete, signed URLs, and bucket-event triggers. Nitric maps it to cloud storage (e.g. AWS S3, GCS, Azure Blob). Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/storage](https://nitric.io/docs/storage)
- **Base URL:** `https://nitric.io/docs/storage`

#### Tags

- Buckets
- Storage
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/storage)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Key-Value Resource

SDK resource for declaring key-value stores with get, set, delete, and query operations. Nitric maps it to a cloud key-value service (e.g. AWS DynamoDB). Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/keyvalue](https://nitric.io/docs/keyvalue)
- **Base URL:** `https://nitric.io/docs/keyvalue`

#### Tags

- Key-Value
- Data Store
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/keyvalue)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Secret Resource

SDK resource for declaring and accessing secrets with versioning. Nitric maps it to a cloud secrets manager (e.g. AWS Secrets Manager). Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/secrets](https://nitric.io/docs/secrets)
- **Base URL:** `https://nitric.io/docs/secrets`

#### Tags

- Secrets
- Security
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/secrets)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Websocket Resource

SDK resource for declaring realtime bidirectional websocket endpoints with connect, disconnect, and message handlers. Nitric provisions the cloud websocket service. Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/websockets](https://nitric.io/docs/websockets)
- **Base URL:** `https://nitric.io/docs/websockets`

#### Tags

- Websockets
- Realtime
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/websockets)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric SQL Database Resource

SDK resource for declaring managed relational (Postgres) databases with migrations. Nitric provisions the cloud database (e.g. AWS RDS, GCP Cloud SQL). Framework primitive, not a hosted API.

- **Human URL:** [https://nitric.io/docs/sql](https://nitric.io/docs/sql)
- **Base URL:** `https://nitric.io/docs/sql`

#### Tags

- SQL
- Databases
- Framework

#### Properties

- [Documentation](https://nitric.io/docs/sql)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric CLI

The Nitric command-line tool (nitric new, nitric start, nitric stack new, nitric up, nitric down) that scaffolds projects, runs local emulation with a dashboard, and deploys or tears down infrastructure via a configured provider. This is local developer tooling, not a hosted API.

- **Human URL:** [https://nitric.io/docs/reference/cli](https://nitric.io/docs/reference/cli)
- **Base URL:** `https://nitric.io/docs/reference/cli`

#### Tags

- CLI
- Tooling
- Deployment

#### Properties

- [Documentation](https://nitric.io/docs/reference/cli)
- [GitHub](https://github.com/nitrictech/cli)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nitric Provider Plugins

Pluggable provider implementations that translate declared Nitric resources into cloud infrastructure on AWS, Google Cloud, or Azure using Pulumi (direct deploy) or Terraform (generated config). Custom providers can be authored in any language. Framework/IaC component, not a hosted API.

- **Human URL:** [https://nitric.io/docs/providers](https://nitric.io/docs/providers)
- **Base URL:** `https://nitric.io/docs/providers`

#### Tags

- Providers
- Pulumi
- Terraform

#### Properties

- [Documentation](https://nitric.io/docs/providers)
- [GitHub](https://github.com/nitrictech/nitric)
- [OpenAPI](openapi/nitric-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nitric.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nitric.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/nitrictech)
- [LinkedIn](https://www.linkedin.com/company/nitric)
- [Website](https://nitric.io/)
- [Documentation](https://nitric.io/docs)
- [Plans](plans/nitric-plans-pricing.yml)
- [Rate Limits](rate-limits/nitric-rate-limits.yml)
- [Fin Ops](finops/nitric-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
