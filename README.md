# Xano (xano)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Xano is a no-code backend / backend-as-a-service that lets users visually build production REST APIs backed by a managed PostgreSQL database and serverless functions. Each workspace auto-generates its own OpenAPI/Swagger for the user-built API groups, and a separate per-instance Metadata API lets you manage tables, schema, records, files, and branches programmatically with Bearer auth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/xano/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/xano/refs/heads/main/apis.yml)

## Tags

- No Code
- Backend as a Service
- BaaS
- API Builder
- Database
- Serverless

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Xano Metadata Tables & Schema API

Programmatically create, read, update, and delete database tables, their column schema, and indexes within a Xano workspace using the per-instance Metadata API.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api/tables-and-schema](https://docs.xano.com/xano-features/metadata-api/tables-and-schema)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- Tables
- Schema
- Indexes

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api/tables-and-schema)
- [API Reference](https://docs.xano.com/xano-features/metadata-api)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xano.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xano.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xano Metadata Records & Content API

Browse, retrieve, create, update, search, and delete database records (table content) individually or in batches through the Metadata API content endpoints.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api/content](https://docs.xano.com/xano-features/metadata-api/content)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- Records
- Content
- CRUD

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api/content)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xano.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xano.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xano Metadata Files API

Upload, list, and delete files in a workspace file library, including batch deletion, via the Metadata API files endpoints.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api](https://docs.xano.com/xano-features/metadata-api)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- Files
- Storage
- Media

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xano.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xano.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xano Metadata Branches & Workspace API

Inspect workspace details, list and delete branches, and export or import workspace schema and data archives through the Metadata API workspace endpoints.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api](https://docs.xano.com/xano-features/metadata-api)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- Branches
- Workspace
- Import Export

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xano.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xano.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xano Metadata API Groups & Endpoints API

Create and manage API groups and their endpoints, and retrieve the auto-generated OpenAPI/Swagger document for the user-built APIs each workspace exposes.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api](https://docs.xano.com/xano-features/metadata-api)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- API Groups
- Endpoints
- OpenAPI

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xano.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xano.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xano Generated User APIs

The REST APIs that Xano users build visually. Each API group is served at its own /api:{token} path on the instance and auto-generates its own OpenAPI/Swagger document; surface, paths, and auth are defined per workspace by the builder.

- **Human URL:** [https://docs.xano.com/connecting-to-a-front-end/fundamentals](https://docs.xano.com/connecting-to-a-front-end/fundamentals)
- **Base URL:** `https://{instance}.xano.io/api:{api_group}`

#### Tags

- Generated API
- REST
- No Code
- OpenAPI

#### Properties

- [Documentation](https://docs.xano.com/connecting-to-a-front-end/fundamentals)
- [API Reference](https://docs.xano.com/xano-features/metadata-api)

### Xano Metadata Auth & Access API

Identify the authenticated user and enumerate accessible workspaces. The Metadata API is authenticated with scoped Bearer access tokens generated from instance settings with CRUD permission scopes.

- **Human URL:** [https://docs.xano.com/xano-features/metadata-api](https://docs.xano.com/xano-features/metadata-api)
- **Base URL:** `https://{instance}.xano.io/api:meta`

#### Tags

- Metadata API
- Authentication
- Access Tokens
- Bearer

#### Properties

- [Documentation](https://docs.xano.com/xano-features/metadata-api)
- [OpenAPI](openapi/xano-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/xano-inc)
- [LinkedIn](https://www.linkedin.com/company/xano)
- [Website](https://www.xano.com)
- [Documentation](https://docs.xano.com)
- [Plans](plans/xano-plans-pricing.yml)
- [Rate Limits](rate-limits/xano-rate-limits.yml)
- [Fin Ops](finops/xano-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
