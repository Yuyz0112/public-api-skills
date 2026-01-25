# GET /zones/{zone_id}/dns_analytics/report

**Resource:** [DNS Analytics](../resources/DNS-Analytics.md)
**Table**
**Operation ID:** `dns-analytics-table`

Retrieves a list of summarised aggregate metrics over a given time period.

See [Analytics API properties](https://developers.cloudflare.com/dns/reference/analytics-api-properties/) for detailed information about the available query parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | dns-analytics_identifier | Yes |  |
| `metrics` | query | dns-analytics_metrics | No |  |
| `dimensions` | query | dns-analytics_dimensions | No |  |
| `since` | query | dns-analytics_since | No |  |
| `until` | query | dns-analytics_until | No |  |
| `limit` | query | dns-analytics_limit | No |  |
| `sort` | query | dns-analytics_sort | No |  |
| `filters` | query | dns-analytics_filters | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Table response |
| 4XX | Table response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
