# GET /accounts/{account_id}/workers/scripts/{script_name}/tails

**Resource:** [Worker Tail Logs](../resources/Worker-Tail-Logs.md)
**List Tails**
**Operation ID:** `get--accounts-{account_id}-workers-scripts-{script_name}-tails`

Get list of tails currently deployed on a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Tails response. |
| 4XX | List Tails response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
