# Sonar

Sonar (SonarSource) provides code quality and security analysis tools including SonarQube (self-hosted), SonarCloud (cloud), and SonarLint (IDE plugin) for continuous code quality inspection across 30+ programming languages.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml)

## Tags

CI/CD, Code Quality, DevOps, Security, SonarCloud, SonarQube, Static Analysis

## APIs

### SonarQube Web API

REST API for SonarQube Server — project management, quality gates, issues, rules, and CI/CD integrations.

- **Documentation:** [https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/](https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/)
- **Reference:** [https://api-docs.sonarsource.com/](https://api-docs.sonarsource.com/)

### SonarCloud API

Cloud-based code quality API for GitHub, GitLab, Bitbucket, and Azure DevOps organizations.

- **Documentation:** [https://sonarcloud.io/web_api](https://sonarcloud.io/web_api)
- **Getting Started:** [https://docs.sonarcloud.io/](https://docs.sonarcloud.io/)
- **OpenAPI:** [openapi/sonar-sonarcloud-api-openapi.yml](openapi/sonar-sonarcloud-api-openapi.yml)

**Operations:**
- `GET /organizations/search` — Search Organizations
- `GET /projects/search` — Search Projects
- `GET /issues/search` — Search Issues
- `GET /qualitygates/list` — List Quality Gates
- `GET /qualitygates/project_status` — Get Quality Gate Status
- `GET /measures/component` — Get Component Measures
- `GET /user_tokens/search` — Search User Tokens
- `POST /user_tokens/generate` — Generate User Token

## Artifacts

### OpenAPI

- [openapi/sonar-sonarcloud-api-openapi.yml](openapi/sonar-sonarcloud-api-openapi.yml) — SonarCloud API specification

### JSON Schemas

- [json-schema/sonar-organization-schema.json](json-schema/sonar-organization-schema.json) — SonarCloud organization
- [json-schema/sonar-issue-schema.json](json-schema/sonar-issue-schema.json) — Code issue (bug, vulnerability, code smell)

### JSON Structure

- [json-structure/sonar-sonarcloud-structure.json](json-structure/sonar-sonarcloud-structure.json) — SonarCloud API data entity structures

### JSON-LD

- [json-ld/sonar-context.jsonld](json-ld/sonar-context.jsonld) — Linked data context for Sonar resources

### Spectral Rules

- [rules/sonar-rules.yml](rules/sonar-rules.yml) — API governance rules for Sonar API conventions

### Naftiko Capabilities

| Capability | Description |
|---|---|
| [capabilities/cloud-code-quality.yaml](capabilities/cloud-code-quality.yaml) | Cloud code quality governance workflow (8 tools) |
| [capabilities/shared/sonarcloud-api.yaml](capabilities/shared/sonarcloud-api.yaml) | Shared: SonarCloud API (8 tools) |

### Examples

- [examples/sonar-search-organizations-example.json](examples/sonar-search-organizations-example.json) — Search organizations response
- [examples/sonar-quality-gate-status-example.json](examples/sonar-quality-gate-status-example.json) — Quality gate passing status

### Vocabulary

- [vocabulary/sonar-vocabulary.yml](vocabulary/sonar-vocabulary.yml) — Sonar domain vocabulary (Clean Code, quality gates, CI/CD)

## Common Properties

- [Website](https://www.sonarsource.com/)
- [Blog](https://www.sonarsource.com/blog/)
- [GitHub Organization](https://github.com/SonarSource)
- [Community](https://community.sonarsource.com/)
- [Status](https://status.sonarsource.com/)
- [Pricing](https://www.sonarsource.com/plans-and-pricing/)
- [Terms of Service](https://www.sonarsource.com/terms/)
- [Privacy Policy](https://www.sonarsource.com/privacy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
