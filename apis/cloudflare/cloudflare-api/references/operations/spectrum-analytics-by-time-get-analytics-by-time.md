# GET /zones/{zone_id}/spectrum/analytics/events/bytime

**Resource:** [Spectrum Analytics](../resources/Spectrum-Analytics.md)
**Get analytics by time**
**Operation ID:** `spectrum-analytics-(-by-time)-get-analytics-by-time`

Retrieves a list of aggregate metrics grouped by time interval.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | spectrum-analytics_identifier | Yes |  |
| `dimensions` | query | spectrum-analytics_dimensions | No |  |
| `sort` | query | spectrum-analytics_sort | No |  |
| `until` | query | spectrum-analytics_until | No |  |
| `metrics` | query | spectrum-analytics_metrics | No |  |
| `filters` | query | spectrum-analytics_filters | No |  |
| `since` | query | spectrum-analytics_since | No |  |
| `time_delta` | query | enum: year, quarter, month... | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get analytics by time response |
| 4xx | Get analytics by time response failure |

**Success Response Schema:**

[spectrum-analytics_query-response-single](../schemas/spectrum-analytics/spectrum-analytics-query-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
