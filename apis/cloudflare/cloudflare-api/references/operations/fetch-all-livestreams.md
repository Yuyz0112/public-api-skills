# GET /accounts/{account_id}/realtime/kit/{app_id}/livestreams

**Resource:** [Live streams](../resources/Live-streams.md)
**Fetch all livestreams**
**Operation ID:** `fetch_all_livestreams`

Returns details of livestreams associated with the given App ID. It includes livestreams created by your App and RealtimeKit meetings that are livestreamed by your App. If you only want details of livestreams created by your App and not RealtimeKit meetings, you can use the `exclude_meetings` query parameter.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `exclude_meetings` | query | boolean | No | Exclude the RealtimeKit meetings that are livestreamed. |
| `per_page` | query | integer | No | Number of results per page. |
| `page_no` | query | integer | No | The page number from which you want your page search results to be displayed. |
| `status` | query | enum: LIVE, IDLE, ERRORED... | No | Specifies the status of the operation. |
| `start_time` | query | string (date-time) | No | Specify the start time range in ISO format to access the live stream. |
| `end_time` | query | string (date-time) | No | Specify the end time range in ISO format to access the live stream. |
| `sort_order` | query | enum: ASC, DSC | No | Specifies the sorting order for the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
