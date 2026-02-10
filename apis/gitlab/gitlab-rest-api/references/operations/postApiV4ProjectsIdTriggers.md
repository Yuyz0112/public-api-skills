# POST /api/v4/projects/{id}/triggers

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Create a trigger token**
**Operation ID:** `postApiV4ProjectsIdTriggers`

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
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTrigger](../schemas/APIEntitiesTrigger/APIEntitiesTrigger.md)

