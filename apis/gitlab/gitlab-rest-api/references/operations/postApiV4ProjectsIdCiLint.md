# POST /api/v4/projects/{id}/ci/lint

**Resource:** [CI lint](../resources/CI-lint.md)
**Validate a CI YAML configuration with a namespace**
**Operation ID:** `postApiV4ProjectsIdCiLint`

Checks if CI/CD YAML configuration is valid. This endpoint has namespace specific context

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesCiLintResult](../schemas/APIEntitiesCiLintResult/APIEntitiesCiLintResult.md)

