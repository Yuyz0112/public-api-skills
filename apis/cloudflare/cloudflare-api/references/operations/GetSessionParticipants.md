# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/participants

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch participants list of a session**
**Operation ID:** `GetSessionParticipants`

Returns a list of participants for the given session ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `include_peer_events` | query | boolean | No | if true, response includes all the peer events of participants. |
| `view` | query | enum: raw, consolidated | No | In breakout room sessions, the view parameter can be set to `raw` for session specific duration for participants or `consolidated` to accumulate breakout room durations. |
| `session_id` | path | string | Yes | ID of the session |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
