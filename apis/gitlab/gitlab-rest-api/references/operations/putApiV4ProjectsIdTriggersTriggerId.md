# PUT /api/v4/projects/{id}/triggers/{trigger_id}

**Resource:** [CI triggers](../resources/CI-triggers.md)
**Update a trigger token**
**Operation ID:** `putApiV4ProjectsIdTriggersTriggerId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `trigger_id` | path | integer | Yes | The trigger token ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesTrigger](../schemas/APIEntitiesTrigger/APIEntitiesTrigger.md)

