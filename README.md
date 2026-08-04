# Maven Central (maven-central)

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
