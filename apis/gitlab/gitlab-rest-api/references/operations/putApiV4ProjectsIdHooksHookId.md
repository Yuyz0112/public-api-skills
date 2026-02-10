# PUT /api/v4/projects/{id}/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Edit project hook**
**Operation ID:** `putApiV4ProjectsIdHooksHookId`

Edits a hook for a specified project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `hook_id` | path | integer | Yes | The ID of the project hook |

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

[APIEntitiesProjectHook](../schemas/APIEntitiesProjectHook/APIEntitiesProjectHook.md)

