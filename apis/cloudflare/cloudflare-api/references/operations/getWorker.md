# GET /accounts/{account_id}/workers/workers/{worker_id}

**Resource:** [Workers](../resources/Workers.md)
**Get Worker**
**Operation ID:** `getWorker`

Get details about a specific Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Worker success. |
| 400 | Bad Request - Missing or invalid parameters. |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
