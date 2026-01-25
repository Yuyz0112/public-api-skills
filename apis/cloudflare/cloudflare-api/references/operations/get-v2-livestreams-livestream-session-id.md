# GET /accounts/{account_id}/realtime/kit/{app_id}/livestreams/sessions/{livestream-session-id}

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch livestream session details using livestream session ID**
**Operation ID:** `get-v2-livestreams-livestream-session-id`

Returns livestream session details for the given livestream session ID. Retrieve the `livestream_session_id`using the `Fetch livestream session details using a session ID` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `livestream-session-id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
