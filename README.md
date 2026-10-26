# Nitric (nitric)

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
