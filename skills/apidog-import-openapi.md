---
name: apidog-import-openapi
description: Use Apidog API to import an OpenAPI or Swagger specification into a project.
api: https://api.apidog.com
operations:
  - importOpenApiData
---

## Steps
1. **Prepare**: Obtain your personal API token and the target `projectId`.
2. **Call**: POST to `/v1/projects/{projectId}/import-openapi` with a JSON body containing the `input` field (either the spec string or an object with `url`).
3. **Handle response**: On `200` you receive an `ImportResult` indicating created/updated endpoints and schemas.
4. **Error handling**: Manage `401` (unauthorized), `404` (project not found), and `422` (validation errors) as documented.

### Idempotency
- The operation is **not** idempotent by default; use `endpointOverwriteBehavior` and `schemaOverwriteBehavior` to control updates.

### Rate limits
- Follow the provider's rate‑limit policy (see rate‑limits section).

### Security
- Bearer token authentication required.
