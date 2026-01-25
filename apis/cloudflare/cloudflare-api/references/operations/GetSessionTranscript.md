# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/transcript

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch the complete transcript for a session**
**Operation ID:** `GetSessionTranscript`

Returns a URL to download the transcript for the session ID in CSV format.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `session_id` | path | string | Yes | ID of the session |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
