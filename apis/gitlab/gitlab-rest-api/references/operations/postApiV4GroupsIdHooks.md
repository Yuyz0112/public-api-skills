# POST /api/v4/groups/{id}/hooks

**Resource:** [Hooks](../resources/Hooks.md)
**Add group hook**
**Operation ID:** `postApiV4GroupsIdHooks`

Adds a hook to a specified group

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |

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

[APIEntitiesGroupHook](../schemas/APIEntitiesGroupHook/APIEntitiesGroupHook.md)

