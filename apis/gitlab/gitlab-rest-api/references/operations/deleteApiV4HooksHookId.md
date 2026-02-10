# DELETE /api/v4/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Delete system hook**
**Operation ID:** `deleteApiV4HooksHookId`

Deletes a system hook

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the system hook |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 404 | Not found |

