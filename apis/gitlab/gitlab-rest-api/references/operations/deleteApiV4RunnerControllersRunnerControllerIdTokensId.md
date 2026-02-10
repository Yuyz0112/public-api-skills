# DELETE /api/v4/runner_controllers/{runner_controller_id}/tokens/{id}

**Resource:** [Runner controller tokens](../resources/Runner-controller-tokens.md)
**Revoke a runner controller token**
**Operation ID:** `deleteApiV4RunnerControllersRunnerControllerIdTokensId`

Revoke a token for a specific runner controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `runner_controller_id` | path | integer | Yes | ID of the runner controller |
| `id` | path | integer | Yes | ID of the runner controller token |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 403 | Forbidden |
| 404 | Not found |

