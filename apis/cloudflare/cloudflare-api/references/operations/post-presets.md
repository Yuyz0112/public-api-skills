# POST /accounts/{account_id}/realtime/kit/{app_id}/presets

**Resource:** [Presets](../resources/Presets.md)
**Create a preset**
**Operation ID:** `post-presets`

Creates a preset belonging to the current App

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
