# GET /api/v4/runner_controllers

**Resource:** [Runners](../resources/Runners.md)
**List runner controllers**
**Operation ID:** `getApiV4RunnerControllers`

Get all runner controllers.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesCiRunnerController](../schemas/APIEntitiesCiRunnerController/APIEntitiesCiRunnerController.md)

