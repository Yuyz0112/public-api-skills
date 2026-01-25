# DELETE /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/participants/{participant_id}

**Resource:** [Meetings](../resources/Meetings.md)
**Delete a participant**
**Operation ID:** `delete_meeting_participant`

Deletes a participant for the given meeting and participant ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. You can fetch the meeting ID using the create a meeting API. |
| `participant_id` | path | string | Yes | ID of the participant. You can fetch the participant ID using the add a participant API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
