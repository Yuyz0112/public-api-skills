# PATCH /accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}/status

**Resource:** [Workflows](../resources/Workflows.md)
**Change status of instance**
**Operation ID:** `wor-change-status-workflow-instance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `instance_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Change status of instance - it can be paused, resumed or terminated. |
| 400 | Bad Request. |
| 404 | Instance not found. |
| 409 | Instance not in a restartable state. |

## Security

- **api_email**
- **api_key**
- **api_token**
