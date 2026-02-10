# POST /api/v4/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**Add new system hook**
**Operation ID:** `postApiV4Hooks`

Add a new system hook

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Validation error |
| 404 | Not found |
| 422 | Unprocessable entity |

**Success Response Schema:**

[APIEntitiesHook](../schemas/APIEntitiesHook/APIEntitiesHook.md)

