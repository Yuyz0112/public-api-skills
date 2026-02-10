# PUT /api/v4/groups/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Edit group hook**
**Operation ID:** `putApiV4GroupsIdHooksHookId`

Edits a hook for a specified group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
| `hook_id` | path | integer | Yes | The ID of the group hook |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesGroupHook](../schemas/APIEntitiesGroupHook/APIEntitiesGroupHook.md)

