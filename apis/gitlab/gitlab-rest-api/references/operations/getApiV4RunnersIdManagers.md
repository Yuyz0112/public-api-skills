# GET /api/v4/runners/{id}/managers

**Resource:** [Runners](../resources/Runners.md)
**Get a list of all runner's managers**
**Operation ID:** `getApiV4RunnersIdManagers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a runner |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiRunnerManager](../schemas/APIEntitiesCiRunnerManager/APIEntitiesCiRunnerManager.md)

