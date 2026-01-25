# POST /accounts/{account_id}/workers/scripts/{script_name}/tails

**Resource:** [Worker Tail Logs](../resources/Worker-Tail-Logs.md)
**Start Tail**
**Operation ID:** `worker-tail-logs-start-tail`

Starts a tail that receives logs and exception from a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Start Tail response. |
| 4XX | Start Tail response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
