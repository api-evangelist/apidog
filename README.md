# Apidog (apidog)

Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and published interactive documentation - all in one collaborative workspace. As of 2026, Apidog also ships native MCP support: the `apidog-mcp-server` feeds API specs to AI coding assistants (Cursor, VS Code + Cline) and the in-app MCP Client visually debugs MCP servers over STDIO and Streamable HTTP with auto OAuth 2.0 configuration.

**URL:** [https://apidog.com/](https://apidog.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

AI Coding, API Design, API Lifecycle, API Testing, Collaboration, Design-First, Documentation, MCP, Mocking, Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-22

## APIs

### Apidog

Apidog's public REST API at `https://api.apidog.com` lets developers programmatically import API specifications into Apidog projects (OpenAPI 3, Swagger 2, Postman Collection v2) and export Apidog projects back out as OpenAPI 2.0, 3.0, or 3.1. The API is versioned via the `X-Apidog-Api-Version` header (current: `2024-03-28`) and authenticated with a personal API access token sent as a Bearer Token.

**Human URL:** [https://apidog.com/](https://apidog.com/)
**Base URL:** `https://api.apidog.com`

#### Tags

API Design, API Lifecycle, Documentation, Import, Export

#### Properties

- [Documentation](https://openapi.apidog.io/)
- [GettingStarted](https://docs.apidog.com/overview-644404m0)
- [OpenAPI](openapi/apidog-apidog-openapi.yml)
- [TermsOfService](https://legal.apidog.com/)
- [Pricing](https://apidog.com/pricing/)
- [Plans](plans/apidog-plans-pricing.yml)
- [RateLimits](rate-limits/apidog-rate-limits.yml)
- [FinOps](finops/apidog-finops.yml)
- [SpectralRules](rules/apidog-rules.yml)
- [JSONSchema](json-schema/apidog-project-schema.json)
- [JSONSchema](json-schema/apidog-import-result-schema.json)
- [JSONSchema](json-schema/apidog-export-result-schema.json)
- [JSONSchema](json-schema/apidog-error-schema.json)
- [JSON-LD](json-ld/apidog-context.jsonld)
- [Vocabulary](vocabulary/apidog-vocabulary.yaml)
- [NaftikoCapability](capabilities/apidog-import-export.yaml)

## Common Properties

- [Website](https://apidog.com/)
- [Documentation](https://docs.apidog.com/)
- [GettingStarted](https://docs.apidog.com/overview-644404m0)
- [Pricing](https://apidog.com/pricing/)
- [Blog](https://apidog.com/blog/)
- [ReleaseNotes](https://apidog.com/blog/product-updates/)
- [StatusPage](https://status.apidog.com/)
- [TermsOfService](https://legal.apidog.com/)
- [Security](https://trust.apidog.com/)
- [Support](https://docs.apidog.com/apidog-support-center-748035m0)
- [GitHubOrganization](https://github.com/Apidog)
- [Roadmap](https://github.com/Apidog/roadmap)
- [CLI](https://docs.apidog.com/installing-and-running-apidog-cli-605135m0) (`npm install -g apidog-cli`)
- [PackageManager](https://www.npmjs.com/package/apidog-cli)
- [MCPServer](https://docs.apidog.com/apidog-mcp-server) (`npx apidog-mcp-server@latest`)
- [MCPClient](https://docs.apidog.com/mcp-client-1930835m0)
- [Locales / SDK Repo](https://github.com/Apidog/apidog-locales)

## Features

| Name | Description |
|------|-------------|
| API Design | Visual OpenAPI/Swagger editor with JSON Schema support, reusable schemas, Git integration, and sprint branches for collaborative development. |
| API Debugging | Multi-protocol support for HTTP, REST, GraphQL, gRPC, SOAP, WebSocket, and SSE with auto-validation of responses against API specs and direct database connectivity. |
| API Testing | Visual test scenarios with CI/CD integration via the apidog-cli npm package, data-driven testing with CSV/JSON datasets, performance testing, and AI-generated test cases. |
| API Mocking | Zero-configuration smart mock generation from specs, cloud-based and local mock servers, and custom mock rules. |
| API Documentation | Auto-generated interactive docs with custom domains, auto-generated SSL certificates, Markdown support, and versioning control. |
| Team Collaboration | Real-time synchronization, sprint branches for parallel development, role-based access control, and SSO support. |
| Apidog MCP Server | Local MCP server (`npx apidog-mcp-server`) that feeds Apidog projects, published docs, or local/remote OpenAPI files to AI coding assistants like Cursor and VS Code + Cline for grounded code generation. |
| Apidog MCP Client | Visual MCP debugging built into the Apidog app. Supports STDIO and Streamable HTTP transports with auto OAuth 2.0 configuration and a Tools / Prompts / Resources tree. |
| AI Test Case Generation | AI Test Engine analyzes API specs to automatically generate positive, error-handling, boundary, and security test cases. |
| AI Schema Descriptions and Mock | AI assistance to modify field descriptions and generate mock data directly inside API schemas. |
| Enterprise Security | SOC 2 Type II posture with GDPR and ISO 27001 alignment, TLS 1.3+ in transit, AES-256 at rest, plus optional on-premises deployment. |

## Use Cases

| Name | Description |
|------|-------------|
| API Design-First Development | Design APIs visually before writing code, enabling frontend and backend teams to work in parallel. |
| Automated API Testing | Build comprehensive regression test suites with CI/CD integration (Jenkins, GitHub Actions, GitLab CI, Bitbucket) via the Apidog CLI. |
| API Documentation Publishing | Automatically generate and publish interactive developer documentation from API specifications, with custom domains and white-labeling on paid tiers. |
| Mock Server Development | Enable frontend development independent of backend completion using intelligent mock data generation from specs. |
| AI-Assisted API Coding | Connect Apidog projects to Cursor or VS Code + Cline through the Apidog MCP Server so AI assistants generate DTOs, controllers, and client code aligned with the real API contract. |
| AI Agent Debugging | Use Apidog MCP Client to visually exercise MCP servers (Tools, Prompts, Resources) over STDIO or Streamable HTTP while building AI-agent backends. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAPI / Swagger | Import and export OpenAPI 2.0 / 3.0 / 3.1 specifications, with Apidog-specific x-apidog-* extensions preserved on export. |
| Postman | Postman Collection v2 import with scripting-syntax compatibility. |
| CI/CD Platforms | Apidog CLI integrates with Jenkins, GitLab CI, GitHub Actions, and Bitbucket Pipelines for automated test runs. |
| Databases | Connects to MySQL, PostgreSQL, Oracle, SQL Server, and ClickHouse for dynamic test data. |
| Credential Vaults | HashiCorp Vault, Azure Key Vault, and AWS Secrets Manager. |
| Enterprise SSO | SAML 2.0, Microsoft Active Directory, OIDC, and SCIM for enterprise identity management. |
| IntelliJ IDEA Plugin | IDEA plugin for JavaDoc-driven API definition generation. |
| Cursor And VS Code + Cline | Through apidog-mcp-server, Apidog projects and OpenAPI files become directly accessible to MCP-compatible AI coding assistants. |

## Plans (Annual Billing)

| Plan | Per Seat / Month | Members | Projects | Highlights |
|------|------------------|---------|----------|------------|
| Free | $0 | up to 4 | 5 | 1 sprint branch per project, unlimited collection runs |
| Basic | $9 ($12 monthly) | unlimited | up to 20 | API versioning, 90-day request history, expanded sprint branches |
| Professional | $18 | unlimited | unlimited | Team-shared variables, white-label docs, faster scheduled imports |
| Enterprise | $27 | unlimited | unlimited | SSO (SAML / AD / OIDC / SCIM), multiple doc sites, 24/7 support, optional on-prem |

Details: [plans/apidog-plans-pricing.yml](plans/apidog-plans-pricing.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apidog API](openapi/apidog-apidog-openapi.yml) - 3 operations across Import And Export (OpenAPI import, OpenAPI export, Postman Collection import)

### JSON Schema

- [apidog-project-schema.json](json-schema/apidog-project-schema.json)
- [apidog-import-result-schema.json](json-schema/apidog-import-result-schema.json)
- [apidog-export-result-schema.json](json-schema/apidog-export-result-schema.json)
- [apidog-error-schema.json](json-schema/apidog-error-schema.json)

### JSON-LD

- [apidog-context.jsonld](json-ld/apidog-context.jsonld)

### Examples

- [apidog-import-openapi-example.json](examples/apidog-import-openapi-example.json)
- [apidog-export-openapi-example.json](examples/apidog-export-openapi-example.json)
- [apidog-import-postman-collection-example.json](examples/apidog-import-postman-collection-example.json)

## Capabilities

Naftiko capabilities organized as per-API definitions.

- [Apidog Import And Export](capabilities/apidog-import-export.yaml) - 3 operations exposed as both REST and MCP adapters

## Vocabulary

- [Apidog Vocabulary](vocabulary/apidog-vocabulary.yaml) - Unified taxonomy across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [apidog-rules.yml](rules/apidog-rules.yml) - 18 Spectral rules across info, paths, operations, tags, parameters, responses, security, and HTTP-method conventions

## Plans, Rate Limits, And FinOps

- [Plans](plans/apidog-plans-pricing.yml) - Per-seat pricing for Free, Basic, Professional, Enterprise (API Commons Plans 0.1)
- [Rate Limits](rate-limits/apidog-rate-limits.yml) - Plan-tier entitlements; Apidog does not publish per-key REST API rate limits
- [FinOps](finops/apidog-finops.yml) - FOCUS-aligned subscription billing model (seat-month, not per-request)

## Notable Findings

- Apidog has shifted hard into the AI / MCP space in 2026: `apidog-mcp-server` (npm) for AI coding assistants, plus an in-app MCP Client with STDIO / Streamable HTTP / OAuth 2.0 auto-config for visually debugging AI-agent backends.
- The public REST API surface is narrow: only 3 operations, all under Import And Export. There is no public Projects, Branches, Endpoints, Schemas, Environments, Members, or Test Scenarios CRUD API published.
- GitHub org `Apidog` is light: 4 public repos (roadmap, apidog-locales, .github, apidog-request-proxy-agent - the latter currently empty). No official SDK repo, no MCP server source repo published, no public OpenAPI spec repo.
- The Apidog CLI (`apidog-cli` on npm) drives the CI/CD test surface and is well documented with ~30 flags; it is separate from the public REST API.

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
