# Apidog (apidog)
Apidog is a complete set of tools that connects the entire API lifecycle, helping R&D teams implement best practices for API Design-first development. It provides API design, debugging, testing, mocking, and documentation capabilities in a single collaborative platform with multi-protocol support including HTTP, GraphQL, gRPC, WebSocket, and SOAP.

**URL:** [https://apidog.com/](https://apidog.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Design, API Lifecycle, API Testing, Collaboration, Design-First, Documentation, Mocking, Platform

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### Apidog
Apidog's public REST API allows developers to programmatically interact with Apidog projects for importing and exporting API specifications, managing endpoints, schemas, environments, and more.

**Human URL:** [https://apidog.com/](https://apidog.com/)

#### Tags:

 - API Design, API Lifecycle, Documentation, Import, Export

#### Properties

- [Documentation](https://openapi.apidog.io/)
- [GettingStarted](https://docs.apidog.com/overview-644404m0)
- [OpenAPI](openapi/apidog-apidog-openapi.yml)
- [TermsOfService](https://legal.apidog.com/)
- [Pricing](https://apidog.com/pricing/)
- [JSONSchema](json-schema/apidog-project-schema.json)
- [JSONSchema](json-schema/apidog-import-result-schema.json)
- [JSONSchema](json-schema/apidog-export-result-schema.json)
- [JSONSchema](json-schema/apidog-error-schema.json)
- [JSON-LD](json-ld/apidog-context.jsonld)

## Common Properties

- [Website](https://apidog.com/)
- [Documentation](https://docs.apidog.com/)
- [GettingStarted](https://docs.apidog.com/overview-644404m0)
- [Pricing](https://apidog.com/pricing/)
- [Blog](https://apidog.com/blog/)
- [ReleaseNotes](https://apidog.com/blog/product-updates/)
- [TermsOfService](https://legal.apidog.com/)
- [Security](https://trust.apidog.com/)
- [Support](https://docs.apidog.com/apidog-support-center-748035m0)
- [GitHubOrganization](https://github.com/Apidog)

## Features

| Name | Description |
|------|-------------|
| API Design | Visual OpenAPI/Swagger editor with JSON Schema support, reusable schemas, Git integration, and sprint branches for collaborative development. |
| API Debugging | Multi-protocol support for HTTP, REST, GraphQL, SOAP, WebSocket with auto-validation of responses against API specs and database connectivity. |
| API Testing | Visual test scenarios with CI/CD integration, data-driven testing with CSV/JSON datasets, performance testing, and AI-generated test cases. |
| API Mocking | Zero-configuration smart mock generation from specs, cloud-based and local mock servers, and custom mock rules. |
| API Documentation | Auto-generated interactive docs with custom domains, auto-generated SSL certificates, Markdown support, and versioning control. |
| Team Collaboration | Real-time synchronization, sprint branches for parallel development, role-based access control, and SSO support. |
| Enterprise Security | SOC 2 Type II certified, GDPR and ISO 27001 compliant, TLS 1.3+ encryption in transit, AES-256 encryption at rest. |

## Use Cases

| Name | Description |
|------|-------------|
| API Design-First Development | Design APIs visually before writing code, enabling frontend and backend teams to work in parallel. |
| Automated API Testing | Build comprehensive regression test suites with CI/CD integration for automated API quality assurance. |
| API Documentation Publishing | Automatically generate and publish interactive developer documentation from API specifications. |
| Mock Server Development | Enable frontend development independent of backend completion using intelligent mock data generation. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAPI/Swagger | Import and export OpenAPI/Swagger specifications for interoperability with other API tools. |
| Postman | 100% compatible Postman collection import and scripting syntax support. |
| CI/CD Platforms | Integration with Jenkins, GitLab CI, GitHub Actions, and Bitbucket Pipelines for automated testing. |
| Databases | Connect to MySQL, PostgreSQL, Oracle, SQLServer, and ClickHouse for dynamic test data. |
| Credential Vaults | Integration with HashiCorp Vault, Azure Key Vault, and AWS Secrets Manager for secure credential management. |
| Enterprise SSO | Support for SAML 2.0, Microsoft Active Directory, OIDC, and SCIM for enterprise identity management. |
| IntelliJ IDEA Plugin | IDEA plugin for JavaDoc annotation parsing and API definition generation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apidog API](openapi/apidog-apidog-openapi.yml)

### JSON Schema

- [apidog-project-schema.json](json-schema/apidog-project-schema.json)
- [apidog-import-result-schema.json](json-schema/apidog-import-result-schema.json)
- [apidog-export-result-schema.json](json-schema/apidog-export-result-schema.json)
- [apidog-error-schema.json](json-schema/apidog-error-schema.json)

### JSON-LD

- [apidog-context.jsonld](json-ld/apidog-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apidog API](capabilities/shared/apidog.yaml) — 3 operations for API specification import and export

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Lifecycle Management](capabilities/api-lifecycle-management.yaml) | Apidog API | 3 | API Developer, Platform Engineer |

## Vocabulary

- [Apidog Vocabulary](vocabulary/apidog-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 2 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [apidog-spectral-rules.yml](rules/apidog-spectral-rules.yml) — 17 rules across 8 categories enforcing Apidog API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
