# GET /api/v4/groups/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Get group hook**
**Operation ID:** `getApiV4GroupsIdHooksHookId`

Get a specific hook for a group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `hook_id` | path | integer | Yes | The ID of a group hook |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesGroupHook](../schemas/APIEntitiesGroupHook/APIEntitiesGroupHook.md)

