# Maven Central (maven-central)

Maven Central is the central repository for Java and other JVM-based artifacts, operated by Sonatype. It provides a REST API for searching artifact metadata and a publishing API for deploying open source libraries to the repository.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artifacts
- Java
- JVM
- Maven
- Package Management
- Repository

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Maven Central Search API

REST API for searching and retrieving metadata about artifacts in Maven Central. Supports Solr-based queries for finding Java libraries, their versions, and download statistics.

- **Human URL:** [https://central.sonatype.org/search/](https://central.sonatype.org/search/)
- **Base URL:** `https://search.maven.org/solrsearch`

#### Tags

- Artifacts
- Metadata
- Search

#### Properties

- [Documentation](https://central.sonatype.org/search/rest-api-guide/)
- [Authentication](https://central.sonatype.org/publish/generate-token/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-central-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-central-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maven-central-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-central-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Central Portal Publishing API

API for publishing artifacts to Maven Central through the Sonatype Central Portal, supporting automated deployment pipelines.

- **Human URL:** [https://central.sonatype.com/](https://central.sonatype.com/)
- **Base URL:** `https://central.sonatype.com/api/v1`

#### Tags

- Deployment
- Publishing
- Upload

#### Properties

- [Documentation](https://central.sonatype.org/publish/publish-portal-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-central-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-central-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/maven-central-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-central-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://central.sonatype.com/)
- [Getting Started](https://central.sonatype.org/publish/publish-guide/)
- [Blog](https://blog.sonatype.com/)
- [Status Page](https://status.maven.org/)
- [Terms of Service](https://central.sonatype.org/publish/terms/)
- [GitHub Organization](https://github.com/sonatype)
- [Support](https://central.sonatype.org/support/)
- [Integrations](https://central.sonatype.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
