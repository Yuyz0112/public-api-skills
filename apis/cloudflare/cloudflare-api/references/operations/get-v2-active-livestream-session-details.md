# GET /accounts/{account_id}/realtime/kit/{app_id}/livestreams/{livestream_id}/active-livestream-session

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch active livestream session details**
**Operation ID:** `get-v2-active-livestream-session-details`

Returns details of all active livestreams for the given livestream ID. Retreive the livestream ID using the `Start livestreaming a meeting` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `livestream_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
