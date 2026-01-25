# PUT /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}

**Resource:** [Meetings](../resources/Meetings.md)
**Replace a meeting**
**Operation ID:** `replace_meeting`

Replaces all the details for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. Fetch the meeting ID using the create a meeting API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
