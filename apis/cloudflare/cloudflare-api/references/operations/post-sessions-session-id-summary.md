# POST /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/summary

**Resource:** [Sessions](../resources/Sessions.md)
**Generate summary of Transcripts for the session**
**Operation ID:** `post-sessions-session_id-summary`

Trigger Summary generation of Transcripts for the session ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `session_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 2XX | Success |

## Security

- **api_token**
