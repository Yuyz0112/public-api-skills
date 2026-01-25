# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch details of a session**
**Operation ID:** `GetSessionDetails`

Returns data of the given session ID including recording details.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `include_breakout_rooms` | query | boolean | No | List all breakout rooms |
| `session_id` | path | string | Yes | ID of the session |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
