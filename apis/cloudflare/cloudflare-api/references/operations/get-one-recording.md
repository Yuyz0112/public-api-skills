# GET /accounts/{account_id}/realtime/kit/{app_id}/recordings/{recording_id}

**Resource:** [Recordings](../resources/Recordings.md)
**Fetch details of a recording**
**Operation ID:** `get_one_recording`

Returns details of a recording for the given recording ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `recording_id` | path | string | Yes | ID of the recording |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
