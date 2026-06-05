# Apidog (apidog)

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
