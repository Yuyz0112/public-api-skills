# GET /accounts/{account_id}/workers/scripts/{script_name}/deployments/{deployment_id}

**Resource:** [Worker Deployments](../resources/Worker-Deployments.md)
**Get Deployment**
**Operation ID:** `worker-deployments-get-deployment`

Get information about a Worker Deployment.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `deployment_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Deployment response. |
| 4XX | Get Deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
