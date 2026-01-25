# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-session/mute-all

**Resource:** [Active session](../resources/Active-session.md)
**Mute all participants**
**Operation ID:** `MuteAllParticipants`

Mutes all participants of an active session for the given meeting ID.

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
