# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/{session_id}/livestream-sessions

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch livestream session details using a session ID**
**Operation ID:** `get-v2-livestreamsession-session-meetingId-active-livestream`

Returns livestream session details for the given session ID. Retreive the session ID using the `Fetch all sessions of an App` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `per_page` | query | number | No | Number of results per page. |
| `page_no` | query | number | No | The page number from which you want your page search results to be displayed. |
| `session_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
