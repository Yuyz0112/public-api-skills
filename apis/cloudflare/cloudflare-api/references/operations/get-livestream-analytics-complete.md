# GET /accounts/{account_id}/realtime/kit/{app_id}/analytics/livestreams/overall

**Resource:** [LivestreamAnalytics](../resources/LivestreamAnalytics.md)
**Fetch complete analytics data for your livestreams**
**Operation ID:** `get-livestream-analytics-complete`

Returns livestream analytics for the specified time range.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `start_time` | query | string (date-time) | No | Specify the start time range in ISO format to access the livestream analytics. |
| `end_time` | query | string (date-time) | No | Specify the end time range in ISO format to access the livestream analytics. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
