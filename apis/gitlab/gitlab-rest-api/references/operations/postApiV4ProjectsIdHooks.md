# POST /api/v4/projects/{id}/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**Add project hook**
**Operation ID:** `postApiV4ProjectsIdHooks`

Adds a hook to a specified project

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

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

[APIEntitiesProjectHook](../schemas/APIEntitiesProjectHook/APIEntitiesProjectHook.md)

