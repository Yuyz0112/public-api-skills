# GET /accounts/{account_id}/workers/scripts/{script_name}/schedules

**Resource:** [Worker Cron Trigger](../resources/Worker-Cron-Trigger.md)
**Get Cron Triggers**
**Operation ID:** `worker-cron-trigger-get-cron-triggers`

Fetches Cron Triggers for a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get Cron Triggers response. |
| 4XX | Get Cron Triggers response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
