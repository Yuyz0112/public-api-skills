# GET /accounts/{account_id}/realtime/kit/{app_id}/recordings

**Resource:** [Recordings](../resources/Recordings.md)
**Fetch all recordings for an App**
**Operation ID:** `get_all_recordings`

Returns all recordings for an App. If the `meeting_id` parameter is passed, returns all recordings for the given meeting ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `meeting_id` | query | string (uuid) | No | ID of a meeting. Optional. Will limit results to only this meeting if passed. |
| `expired` | query | boolean | No | If passed, only shows expired/non-expired recordings on RealtimeKit's bucket |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 201 | Created |

## Security

- **api_token**
