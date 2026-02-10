# GET /api/v4/projects/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Get project hook**
**Operation ID:** `getApiV4ProjectsIdHooksHookId`

Get a specific hook for a project

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `hook_id` | path | integer | Yes | The ID of a project hook |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectHook](../schemas/APIEntitiesProjectHook/APIEntitiesProjectHook.md)

