# GET /accounts/{account_id}/workflows/{workflow_name}

**Resource:** [Workflows](../resources/Workflows.md)
**Get Workflow details**
**Operation ID:** `wor-get-workflow-details`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Workflow details. |
| 400 | Workflow has no deployed versions. |
| 404 | Workflow not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
