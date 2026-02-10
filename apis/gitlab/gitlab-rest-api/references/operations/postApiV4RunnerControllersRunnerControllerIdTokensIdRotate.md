# POST /api/v4/runner_controllers/{runner_controller_id}/tokens/{id}/rotate

**Resource:** [Runner controller tokens](../resources/Runner-controller-tokens.md)
**Rotate a runner controller token**
**Operation ID:** `postApiV4RunnerControllersRunnerControllerIdTokensIdRotate`

Rotate an existing token for a specific runner controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `runner_controller_id` | path | integer | Yes | ID of the runner controller |
| `id` | path | integer | Yes | ID of the runner controller token |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesCiRunnerControllerTokenWithToken](../schemas/APIEntitiesCiRunnerControllerTokenWithToken/APIEntitiesCiRunnerControllerTokenWithToken.md)

