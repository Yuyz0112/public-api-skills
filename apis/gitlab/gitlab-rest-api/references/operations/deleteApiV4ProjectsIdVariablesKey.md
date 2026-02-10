# DELETE /api/v4/projects/{id}/variables/{key}

**Resource:** [CI variables](../resources/CI-variables.md)
**Delete an existing variable from a project**
**Operation ID:** `deleteApiV4ProjectsIdVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID of a project or URL-encoded NAMESPACE/PROJECT_NAME of the project owned by the authenticated user |
| `key` | path | string | Yes | The key of a variable |
| `filter` | query | object | No | Available filters: [environment_scope]. Example: filter[environment_scope]=production |
| `filter[environment_scope]` | query | string | No | The environment scope of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Variable Not Found |

