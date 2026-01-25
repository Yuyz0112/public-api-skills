# GET /accounts/{account_id}/workflows/{workflow_name}/versions

**Resource:** [Workflows](../resources/Workflows.md)
**List deployed Workflow versions**
**Operation ID:** `wor-list-workflow-versions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `per_page` | query | number | No |  |
| `page` | query | number | No |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List deployed workflow versions. |
| 400 | Bad Request. |

## Security

- **api_email**
- **api_key**
- **api_token**
