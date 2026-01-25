# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/active-session/kick

**Resource:** [Active session](../resources/Active-session.md)
**Kick participants from an active session**
**Operation ID:** `KickPartcipants`

Kicks one or more participants from an active session using user ID or custom participant ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

## Security

- **api_token**
