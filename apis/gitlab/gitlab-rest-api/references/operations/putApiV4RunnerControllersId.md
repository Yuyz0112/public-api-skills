# PUT /api/v4/runner_controllers/{id}

**Resource:** [Runner controllers](../resources/Runner-controllers.md)
**Update a runner controller**
**Operation ID:** `putApiV4RunnerControllersId`

Update a runner controller by using the ID of the controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of the runner controller |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerController](../schemas/APIEntitiesCiRunnerController/APIEntitiesCiRunnerController.md)

