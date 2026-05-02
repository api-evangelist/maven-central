# Maven Central (maven-central)

Maven Central is the central repository for Java and other JVM-based artifacts, operated by Sonatype. It provides a REST API for searching artifact metadata and a publishing API for deploying open source libraries to the repository.

**URL:** [https://central.sonatype.com/](https://central.sonatype.com/)

## Tags

- Artifacts, Java, JVM, Maven, Package Management, Repository

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Maven Central Search API

REST API for searching and retrieving metadata about artifacts in Maven Central. Supports Solr-based queries for finding Java libraries, their versions, and download statistics.

**Human URL:** [https://central.sonatype.org/search/](https://central.sonatype.org/search/)

**Base URL:** `https://search.maven.org/solrsearch`

#### Tags

- Artifacts, Metadata, Search

#### Properties

- [Documentation](https://central.sonatype.org/search/rest-api-guide/)
- [Authentication](https://central.sonatype.org/publish/generate-token/)
- [OpenAPI](openapi/maven-central-search-openapi.yml)

### Central Portal Publishing API

API for publishing artifacts to Maven Central through the Sonatype Central Portal, supporting automated deployment pipelines.

**Human URL:** [https://central.sonatype.com/](https://central.sonatype.com/)

**Base URL:** `https://central.sonatype.com/api/v1`

#### Tags

- Deployment, Publishing, Upload

#### Properties

- [Documentation](https://central.sonatype.org/publish/publish-portal-api/)
- [OpenAPI](openapi/maven-central-portal-openapi.yml)

## Common Properties

- [Portal](https://central.sonatype.com/)
- [Getting Started](https://central.sonatype.org/publish/publish-guide/)
- [Blog](https://blog.sonatype.com/)
- [Status](https://status.maven.org/)
- [Terms of Service](https://central.sonatype.org/publish/terms/)
- [GitHub Organization](https://github.com/sonatype)
- [Support](https://central.sonatype.org/support/)

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
