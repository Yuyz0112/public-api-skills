# GET /accounts/{account_id}/workflows/{workflow_name}/instances/terminate

**Resource:** [Workflows](../resources/Workflows.md)
**Get status of the job responsible for terminate all instances of a workflow**
**Operation ID:** `wor-status-terminate-workflow-instances`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get status of the job responsible for terminate all instances of a workflow. |
| 400 | Input Validation Error. |
| 404 | Workflow Name not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
