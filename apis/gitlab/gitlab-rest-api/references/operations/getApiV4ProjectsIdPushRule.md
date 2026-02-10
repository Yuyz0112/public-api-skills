# GET /api/v4/projects/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Get project push rule**
**Operation ID:** `getApiV4ProjectsIdPushRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesProjectPushRule](../schemas/APIEntitiesProjectPushRule/APIEntitiesProjectPushRule.md)

