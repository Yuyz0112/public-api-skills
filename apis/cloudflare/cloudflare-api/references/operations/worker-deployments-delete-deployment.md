# DELETE /accounts/{account_id}/workers/scripts/{script_name}/deployments/{deployment_id}

**Resource:** [Worker Deployments](../resources/Worker-Deployments.md)
**Delete Deployment**
**Operation ID:** `worker-deployments-delete-deployment`

Delete a Worker Deployment. The latest deployment, which is actively serving traffic, cannot be deleted. All other deployments can be deleted.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `deployment_id` | path | string (uuid) | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Deployment response. |
| 4XX | Delete Deployment response failure. |

**Success Response Schema:**

[workers_api-response-common](../schemas/workers/workers-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
