# GET /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}

**Resource:** [Meetings](../resources/Meetings.md)
**Fetch a meeting for an App**
**Operation ID:** `get_meeting`

Returns a meeting details in an App for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `name` | query | string | No |  |
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting. Fetch the meeting ID using the create a meeting API. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 500 | (reference) |

## Security

- **api_token**
