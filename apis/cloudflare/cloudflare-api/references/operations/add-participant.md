# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants

**Resource:** [Meetings](../resources/Meetings.md)
**Add a participant**
**Operation ID:** `add_participant`

Adds a participant to the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. Fetch the meeting ID using the create a meeting API. |

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
