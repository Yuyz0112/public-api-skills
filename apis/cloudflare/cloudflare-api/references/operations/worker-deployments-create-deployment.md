# POST /accounts/{account_id}/workers/scripts/{script_name}/deployments

**Resource:** [Worker Deployments](../resources/Worker-Deployments.md)
**Create Deployment**
**Operation ID:** `worker-deployments-create-deployment`

Deployments configure how [Worker Versions](https://developers.cloudflare.com/api/operations/worker-versions-list-versions) are deployed to traffic. A deployment can consist of one or two versions of a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |
| `force` | query | boolean | No | If set to true, the deployment will be created even if normally blocked by something such rolling back to an older version when a secret has changed. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_deployment](../schemas/workers/workers-deployment.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Deployment response. |
| 4XX | Create Deployment response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
