# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}/token

**Resource:** [Meetings](../resources/Meetings.md)
**Refresh participant's authentication token**
**Operation ID:** `regenerate_token`

Regenerates participant's authentication token for the given meeting and participant ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. You can fetch the meeting ID using the create a meeting API. |
| `participant_id` | path | string | Yes | ID of the participant. You can fetch the participant ID using the add a  participant API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
