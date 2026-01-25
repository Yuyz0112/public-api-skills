# GET /accounts/{account_id}/realtime/kit/{app_id}/meetings

**Resource:** [Meetings](../resources/Meetings.md)
**Fetch all meetings for an App**
**Operation ID:** `get_all_meetings`

Returns all meetings for the given App ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
