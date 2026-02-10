# DELETE /api/v4/projects/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Delete a project hook**
**Operation ID:** `deleteApiV4ProjectsIdHooksHookId`

Removes a hook from a project. This is an idempotent method and can be called multiple times. Either the hook is available or not.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `hook_id` | path | integer | Yes | The ID of the project hook |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Not found |

