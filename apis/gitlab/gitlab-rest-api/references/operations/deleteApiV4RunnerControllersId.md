# DELETE /api/v4/runner_controllers/{id}

**Resource:** [Runner controllers](../resources/Runner-controllers.md)
**Delete a runner controller**
**Operation ID:** `deleteApiV4RunnerControllersId`

Delete a runner controller by using the ID of the controller.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of the runner controller |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not found |

