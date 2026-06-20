# Xano (xano)

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
