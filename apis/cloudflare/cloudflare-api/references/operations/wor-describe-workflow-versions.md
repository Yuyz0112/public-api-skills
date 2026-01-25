# GET /accounts/{account_id}/workflows/{workflow_name}/versions/{version_id}

**Resource:** [Workflows](../resources/Workflows.md)
**Get Workflow version details**
**Operation ID:** `wor-describe-workflow-versions`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `version_id` | path | string (uuid) | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get specific version details. |
| 400 | Bad Request. |
| 404 | Version not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
