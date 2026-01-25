# GET /accounts/{account_id}/builds/workers/{external_script_id}/triggers

**Resource:** [Workers](../resources/Workers.md)
**List triggers by script**
**Operation ID:** `listTriggersByScript`

Get all triggers for a specific worker script

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `external_script_id` | path | string | Yes | External script identifier |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Triggers retrieved successfully |

## Security

- **api_token**
- **api_email**
- **api_key**
