# GET /accounts/{account_id}/realtime/kit/{app_id}/livestreams/{livestream_id}

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch livestream details using livestream ID**
**Operation ID:** `get-v2-livestream-session-livestream-id`

Returns details of a livestream with sessions for the given livestream ID. Retreive the livestream ID using the `Start livestreaming a meeting` API.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `page_no` | query | integer | No | The page number from which you want your page search results to be displayed. |
| `per_page` | query | integer | No | Number of results per page. |
| `livestream_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
