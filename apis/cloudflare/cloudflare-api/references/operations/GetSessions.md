# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch all sessions of an App**
**Operation ID:** `GetSessions`

Returns details of all sessions of an App.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `search` | query | string | No | Search string that matches sessions based on meeting title, meeting ID, and session ID |
| `associated_id` | query | string | No | ID of the meeting that sessions should be associated with |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
