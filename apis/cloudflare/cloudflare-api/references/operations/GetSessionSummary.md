# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/summary

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch summary of transcripts for a session**
**Operation ID:** `GetSessionSummary`

Returns a Summary URL to download the Summary of Transcripts for the session ID as plain text.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `session_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
