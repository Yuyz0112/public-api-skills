# GET /api/v4/runner_controllers/{runner_controller_id}/tokens/{id}

**Resource:** [Runner controller tokens](../resources/Runner-controller-tokens.md)
**Get single runner controller token**
**Operation ID:** `getApiV4RunnerControllersRunnerControllerIdTokensId`

Get a token for a specific runner controller by using the ID of the token.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `runner_controller_id` | path | integer | Yes | ID of the runner controller |
| `id` | path | integer | Yes | ID of the runner controller token |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerControllerToken](../schemas/APIEntitiesCiRunnerControllerToken/APIEntitiesCiRunnerControllerToken.md)

