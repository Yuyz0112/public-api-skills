# GET /accounts/{account_id}/workers/scripts/{script_name}/deployments

**Resource:** [Worker Deployments](../resources/Worker-Deployments.md)
**List Deployments**
**Operation ID:** `worker-deployments-list-deployments`

List of Worker Deployments. The first deployment in the list is the latest deployment actively serving traffic.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Deployments response. |
| 4XX | List Deployments response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
