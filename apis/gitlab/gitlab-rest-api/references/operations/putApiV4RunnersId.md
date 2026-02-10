# PUT /api/v4/runners/{id}

**Resource:** [Runners](../resources/Runners.md)
**Update runner's details**
**Operation ID:** `putApiV4RunnersId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | No access granted |
| 404 | Runner not found |

**Success Response Schema:**

[APIEntitiesCiRunnerDetails](../schemas/APIEntitiesCiRunnerDetails/APIEntitiesCiRunnerDetails.md)

