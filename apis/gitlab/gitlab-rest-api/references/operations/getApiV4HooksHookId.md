# GET /api/v4/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Get system hook**
**Operation ID:** `getApiV4HooksHookId`

Get a system hook by its ID. Introduced in GitLab 14.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the system hook |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesHook](../schemas/APIEntitiesHook/APIEntitiesHook.md)

