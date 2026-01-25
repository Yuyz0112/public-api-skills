# GET /accounts/{account_id}/realtime/kit/{app_id}/presets

**Resource:** [Presets](../resources/Presets.md)
**Fetch all presets**
**Operation ID:** `get-presets`

Fetches all the presets belonging to an App.

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
