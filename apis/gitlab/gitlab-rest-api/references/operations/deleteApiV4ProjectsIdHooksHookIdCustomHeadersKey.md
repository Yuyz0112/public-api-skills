# DELETE /api/v4/projects/{id}/hooks/{hook_id}/custom_headers/{key}

**Resource:** [projects](../resources/projects.md)
**Un-Set a custom header**
**Operation ID:** `deleteApiV4ProjectsIdHooksHookIdCustomHeadersKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the hook |
| `key` | path | string | Yes | The key of the custom header |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

