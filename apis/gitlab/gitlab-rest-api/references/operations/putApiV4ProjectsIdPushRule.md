# PUT /api/v4/projects/{id}/push_rule

**Resource:** [Push rules](../resources/Push-rules.md)
**Update an existing project push rule**
**Operation ID:** `putApiV4ProjectsIdPushRule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

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

[APIEntitiesProjectPushRule](../schemas/APIEntitiesProjectPushRule/APIEntitiesProjectPushRule.md)

