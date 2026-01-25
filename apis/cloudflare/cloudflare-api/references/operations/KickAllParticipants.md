# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-session/kick-all

**Resource:** [Active session](../resources/Active-session.md)
**Kick all participants**
**Operation ID:** `KickAllParticipants`

Kicks all participants from an active session for the given meeting ID.

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
