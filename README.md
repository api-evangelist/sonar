# Sonar (sonar)

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

Sonar (SonarSource) provides code quality and security analysis tools for developers. Products include SonarQube (self-hosted), SonarCloud (cloud-hosted), and SonarLint (IDE plugin), offering continuous inspection through static code analysis across 30+ programming languages.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonar/refs/heads/main/apis.yml)

## Tags

- CI/CD
- Code Quality
- DevOps
- Security
- SonarCloud
- SonarQube
- Static Analysis

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### SonarQube Web API

REST API for interacting with SonarQube Server, enabling management of projects, quality gates, issues, rules, users, and CI/CD integrations. Uses token-based authentication.

- **Human URL:** [https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/](https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/)

#### Tags

- Code Quality
- DevOps
- Security
- SonarQube
- Static Analysis
- Technical Debt

#### Properties

- [Documentation](https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/)
- [Reference](https://api-docs.sonarsource.com/)
- [Authentication](https://docs.sonarsource.com/sonarqube-server/latest/extension-guide/web-api/)
- [Postman Collection](collections/sonar-sonarcloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sonar-sonarcloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SonarCloud API

Cloud-based code quality and security analysis API for analyzing code repositories from GitHub, GitLab, Bitbucket, and Azure DevOps organizations. Provides organization management, project analysis, issue tracking, quality gate monitoring, and metric retrieval.

- **Human URL:** [https://sonarcloud.io/web_api](https://sonarcloud.io/web_api)

#### Tags

- Bitbucket
- CI/CD
- Cloud
- Code Quality
- GitHub
- GitLab
- SonarCloud

#### Properties

- [Documentation](https://sonarcloud.io/web_api)
- [Getting Started](https://docs.sonarcloud.io/)
- [Authentication](https://docs.sonarcloud.io/advanced-setup/api-authentication/)
- [OpenAPI](openapi/sonar-sonarcloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sonar-sonarcloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sonar-sonarcloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sonar-organization-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sonar-issue-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sonar-sonarcloud-structure.json)
- [JSON-LD](json-ld/sonar-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/sonar-rules.yml)
- [Example](examples/sonar-search-organizations-example.json)
- [Example](examples/sonar-quality-gate-status-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sonarsource)
- [Website](https://www.sonarsource.com/)
- [Blog](https://www.sonarsource.com/blog/)
- [GitHub Organization](https://github.com/SonarSource)
- [Support](https://community.sonarsource.com/)
- [Status Page](https://status.sonarsource.com/)
- [Pricing](https://www.sonarsource.com/plans-and-pricing/)
- [Terms of Service](https://www.sonarsource.com/terms/)
- [Privacy Policy](https://www.sonarsource.com/privacy/)
- [Vocabulary](vocabulary/sonar-vocabulary.yml)
- [Integrations](https://www.sonarsource.com/integrations/)
- [M C P Server](https://github.com/SonarSource/sonarqube-mcp-server)
- [L L Ms Txt](https://docs.sonarsource.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
