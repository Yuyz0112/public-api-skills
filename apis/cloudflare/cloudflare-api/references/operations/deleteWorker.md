# DELETE /accounts/{account_id}/workers/workers/{worker_id}

**Resource:** [Workers](../resources/Workers.md)
**Delete Worker**
**Operation ID:** `deleteWorker`

Delete a Worker and all its associated resources (versions, deployments, etc.).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete Worker success. |
| 400 | Bad Request - Missing or invalid parameters. |
| 401 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[workers_api-response-common](../schemas/workers/workers-api-response-common.md)

## Security

- **api_token**
- **api_email**
- **api_key**
