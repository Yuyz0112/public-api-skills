# GET /accounts/{account_id}/realtime/kit/{app_id}/analytics/daywise

**Resource:** [Analytics](../resources/Analytics.md)
**Fetch day-wise session and recording analytics data for an App**
**Operation ID:** `get-org-analytics`

Returns day-wise session and recording analytics data of an App for the specified time range start_date to end_date. If start_date and end_date are not provided, the default time range is set from 30 days ago to the current date.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

## Security

- **api_token**
