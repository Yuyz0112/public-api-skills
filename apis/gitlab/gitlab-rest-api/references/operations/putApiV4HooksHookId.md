# PUT /api/v4/hooks/{hook_id}

**Resource:** [Hooks](../resources/Hooks.md)
**Edit system hook**
**Operation ID:** `putApiV4HooksHookId`

Edits a system hook

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `hook_id` | path | integer | Yes | The ID of the system hook |

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

[APIEntitiesHook](../schemas/APIEntitiesHook/APIEntitiesHook.md)

