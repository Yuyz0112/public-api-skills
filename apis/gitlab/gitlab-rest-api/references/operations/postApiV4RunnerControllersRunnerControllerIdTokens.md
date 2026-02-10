# POST /api/v4/runner_controllers/{runner_controller_id}/tokens

**Resource:** [Runner controller tokens](../resources/Runner-controller-tokens.md)
**Create a runner controller token**
**Operation ID:** `postApiV4RunnerControllersRunnerControllerIdTokens`

Create a new token for a specific runner controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `runner_controller_id` | path | integer | Yes | ID of the runner controller |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerControllerToken](../schemas/APIEntitiesCiRunnerControllerToken/APIEntitiesCiRunnerControllerToken.md)

