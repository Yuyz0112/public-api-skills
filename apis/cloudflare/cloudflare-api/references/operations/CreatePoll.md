# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-session/poll

**Resource:** [Active session](../resources/Active-session.md)
**Create a poll**
**Operation ID:** `CreatePoll`

Creates a new poll in an active session for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |
| 400 | Bad Request |

## Security

- **api_token**
