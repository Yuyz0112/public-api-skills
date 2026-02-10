# PUT /api/v4/projects/{id}/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Update an existing variable from a project**
**Operation ID:** `putApiV4ProjectsIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID of a project or URL-encoded NAMESPACE/PROJECT_NAME of the project owned by the authenticated user |
| `key` | path | string | No | The key of a variable |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Variable Not Found |

**Success Response Schema:**

[APIEntitiesCiVariable](../schemas/APIEntitiesCiVariable/APIEntitiesCiVariable.md)

