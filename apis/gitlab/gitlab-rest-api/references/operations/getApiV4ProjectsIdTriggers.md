# GET /api/v4/projects/{id}/triggers

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Get trigger tokens list**
**Operation ID:** `getApiV4ProjectsIdTriggers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTrigger](../schemas/APIEntitiesTrigger/APIEntitiesTrigger.md)

