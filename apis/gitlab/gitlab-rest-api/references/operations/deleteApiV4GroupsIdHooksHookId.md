# DELETE /api/v4/groups/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Delete group hook**
**Operation ID:** `deleteApiV4GroupsIdHooksHookId`

Removes a hook from a group. This is an idempotent method and can be called multiple times. Either the hook is available or not.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `hook_id` | path | integer | Yes | The ID of the group hook |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Not found |

