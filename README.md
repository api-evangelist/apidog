# Apidog (apidog)

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

Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and published interactive documentation - all in a single collaborative workspace. As of 2026 Apidog also ships native MCP support: an apidog-mcp-server that feeds API specs to AI coding assistants (Cursor, VS Code + Cline) and an MCP Client inside the desktop app that visually debugs MCP servers over STDIO and Streamable HTTP with auto OAuth 2.0 configuration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apidog/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Coding
- API Design
- API Lifecycle
- API Testing
- Collaboration
- Design-First
- Documentation
- MCP
- Mocking
- Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

## APIs

### Apidog

Apidog's public REST API at https://api.apidog.com lets developers programmatically import API specifications into Apidog projects (OpenAPI 3, Swagger 2, Postman Collection v2) and export Apidog projects back out as OpenAPI 2.0, 3.0, or 3.1. The API is versioned via the X-Apidog-Api-Version header (current: 2024-03-28) and authenticated with a personal API access token sent as a Bearer Token.

- **Human URL:** [https://apidog.com/](https://apidog.com/)
- **Base URL:** `https://api.apidog.com`

#### Tags

- API Design
- API Lifecycle
- Documentation
- Import
- Export

#### Properties

- [Documentation](https://openapi.apidog.io/)
- [Getting Started](https://docs.apidog.com/overview-644404m0)
- [Authentication](https://docs.apidog.com/api-access-tokens)
- [OpenAPI](openapi/apidog-apidog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apidog-apidog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apidog-apidog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Terms of Service](https://legal.apidog.com/)
- [Pricing](https://apidog.com/pricing/)
- [Plans](plans/apidog-plans-pricing.yml)
- [Rate Limits](rate-limits/apidog-rate-limits.yml)
- [Fin Ops](finops/apidog-finops.yml)
- [Spectral Rules](rules/apidog-rules.yml)
- [JSON Schema](json-schema/apidog-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/apidog-import-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/apidog-export-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/apidog-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/apidog-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/apidog-vocabulary.yaml)
- [Example](examples/apidog-import-openapi-example.json)
- [Example](examples/apidog-export-openapi-example.json)
- [Example](examples/apidog-import-postman-collection-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/apidog)
- [Website](https://apidog.com/)
- [Documentation](https://docs.apidog.com/)
- [Getting Started](https://docs.apidog.com/overview-644404m0)
- [Pricing](https://apidog.com/pricing/)
- [Blog](https://apidog.com/blog/)
- [Release Notes](https://apidog.com/blog/product-updates/)
- [Status Page](https://status.apidog.com/)
- [Articles](https://apidog.com/articles/)
- [Terms of Service](https://legal.apidog.com/)
- [Security](https://trust.apidog.com/)
- [Support](https://docs.apidog.com/apidog-support-center-748035m0)
- [GitHub Organization](https://github.com/Apidog)
- [Roadmap](https://github.com/Apidog/roadmap)
- [C L I](https://docs.apidog.com/installing-and-running-apidog-cli-605135m0)
- [Package Manager](https://www.npmjs.com/package/apidog-cli)
- [M C P Server](https://docs.apidog.com/apidog-mcp-server)
- [M C P Server](https://www.npmjs.com/package/apidog-mcp-server)
- [M C P Client](https://docs.apidog.com/mcp-client-1930835m0)
- [SDK](https://github.com/Apidog/apidog-locales)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.apidog.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
