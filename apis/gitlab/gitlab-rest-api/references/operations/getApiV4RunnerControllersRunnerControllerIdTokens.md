# GET /api/v4/runner_controllers/{runner_controller_id}/tokens

**Resource:** [Runners](../resources/Runners.md)
**List runner controller tokens**
**Operation ID:** `getApiV4RunnerControllersRunnerControllerIdTokens`

Get all tokens for a specific runner controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `runner_controller_id` | path | integer | Yes | ID of the runner controller |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerControllerToken](../schemas/APIEntitiesCiRunnerControllerToken/APIEntitiesCiRunnerControllerToken.md)

