# GET /accounts/{account_id}/dns_firewall/{dns_firewall_id}/dns_analytics/report/bytime

**Resource:** [DNS Firewall Analytics](../resources/DNS-Firewall-Analytics.md)
**By Time**
**Operation ID:** `dns-firewall-analytics-by-time`

Retrieves a list of aggregate metrics grouped by time interval.

See [Analytics API properties](https://developers.cloudflare.com/dns/reference/analytics-api-properties/) for detailed information about the available query parameters.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dns_firewall_id` | path | dns-analytics_identifier | Yes |  |
| `account_id` | path | dns-analytics_identifier | Yes |  |
| `metrics` | query | dns-analytics_metrics | No |  |
| `dimensions` | query | dns-analytics_dimensions | No |  |
| `since` | query | dns-analytics_since | No |  |
| `until` | query | dns-analytics_until | No |  |
| `limit` | query | dns-analytics_limit | No |  |
| `sort` | query | dns-analytics_sort | No |  |
| `filters` | query | dns-analytics_filters | No |  |
| `time_delta` | query | dns-analytics_time_delta | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | By Time response |
| 4XX | By Time response failure |

## Security

- **api_token**
- **api_email**
- **api_key**
