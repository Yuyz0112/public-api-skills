# DELETE /api/v4/projects/{id}/hooks/{hook_id}/url_variables/{key}

**Resource:** [projects](../resources/projects.md)
**Un-Set a url variable**
**Operation ID:** `deleteApiV4ProjectsIdHooksHookIdUrlVariablesKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `key` | path | string | Yes | The key of the variable |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

