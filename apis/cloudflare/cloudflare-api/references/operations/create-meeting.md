# POST /accounts/{account_id}/realtime/kit/{app_id}/meetings

**Resource:** [Meetings](../resources/Meetings.md)
**Create a meeting**
**Operation ID:** `create_meeting`

Create a meeting for the given App ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 201 | (reference) |

## Security

- **api_token**
