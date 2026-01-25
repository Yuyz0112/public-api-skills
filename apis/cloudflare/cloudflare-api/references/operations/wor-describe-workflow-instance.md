# GET /accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}

**Resource:** [Workflows](../resources/Workflows.md)
**Get logs and status from instance**
**Operation ID:** `wor-describe-workflow-instance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `instance_id` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get all logs and status from the instance. |
| 400 | Bad Request. |
| 404 | Instance not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
