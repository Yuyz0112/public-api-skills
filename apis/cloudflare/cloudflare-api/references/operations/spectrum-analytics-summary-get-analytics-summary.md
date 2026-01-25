# GET /zones/{zone_id}/spectrum/analytics/events/summary

**Resource:** [Spectrum Analytics](../resources/Spectrum-Analytics.md)
**Get analytics summary**
**Operation ID:** `spectrum-analytics-(-summary)-get-analytics-summary`

Retrieves a list of summarised aggregate metrics over a given time period.

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

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get analytics summary response |
| 4xx | Get analytics summary response failure |

**Success Response Schema:**

[spectrum-analytics_query-response-single](../schemas/spectrum-analytics/spectrum-analytics-query-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
