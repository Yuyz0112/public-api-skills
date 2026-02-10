# GET /api/v4/projects/{id}/triggers/{trigger_id}

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Get specific trigger token of a project**
**Operation ID:** `getApiV4ProjectsIdTriggersTriggerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `trigger_id` | path | integer | Yes | The trigger token ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTrigger](../schemas/APIEntitiesTrigger/APIEntitiesTrigger.md)

