# GET /accounts/{account_id}/realtime/kit/{app_id}/meetings/{meeting_id}/livestream

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch livestream session details for a meeting**
**Operation ID:** `livestream-session-details`

Returns livestream session details for the given meeting ID. Retreive the meeting ID using the `Create a meeting` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page_no` | query | integer | No | The page number from which you want your page search results to be displayed. |
| `per_page` | query | integer | No | Number of results per page. |
| `meeting_id` | path | string (uuid) | Yes | ID of the meeting |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
