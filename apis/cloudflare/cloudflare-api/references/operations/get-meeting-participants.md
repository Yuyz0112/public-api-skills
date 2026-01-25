# GET /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants

**Resource:** [Meetings](../resources/Meetings.md)
**Fetch all participants of a meeting**
**Operation ID:** `get_meeting_participants`

Returns all participants detail for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. Fetch the meeting ID using the create a meeting API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
