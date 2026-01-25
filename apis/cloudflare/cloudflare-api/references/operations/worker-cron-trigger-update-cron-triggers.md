# PUT /accounts/{account_id}/workers/scripts/{script_name}/schedules

**Resource:** [Worker Cron Trigger](../resources/Worker-Cron-Trigger.md)
**Update Cron Triggers**
**Operation ID:** `worker-cron-trigger-update-cron-triggers`

Updates Cron Triggers for a Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `script_name` | path | workers_script_name | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** Array of [workers_schedule](../schemas/workers/workers-schedule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Cron Triggers response. |
| 4XX | Update Cron Triggers response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
