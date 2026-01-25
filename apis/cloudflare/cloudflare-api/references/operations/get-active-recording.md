# GET /accounts/{account_id}/realtime/kit/{app_id}/recordings/active-recording/{meeting_id}

**Resource:** [Recordings](../resources/Recordings.md)
**Fetch active recording**
**Operation ID:** `get_active_recording`

Returns the active recording details for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `meeting_id` | path | string | Yes | ID of the meeting |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 404 | (reference) |

## Security

- **api_token**
