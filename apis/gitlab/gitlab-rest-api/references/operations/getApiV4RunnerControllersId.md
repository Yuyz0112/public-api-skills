# GET /api/v4/runner_controllers/{id}

**Resource:** [Runner controllers](../resources/Runner-controllers.md)
**Get single runner controller**
**Operation ID:** `getApiV4RunnerControllersId`

Get a runner controller by using the ID of the controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of the runner controller |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerController](../schemas/APIEntitiesCiRunnerController/APIEntitiesCiRunnerController.md)

