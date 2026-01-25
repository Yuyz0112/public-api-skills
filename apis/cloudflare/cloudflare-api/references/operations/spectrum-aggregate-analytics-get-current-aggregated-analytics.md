# GET /zones/{zone_id}/spectrum/analytics/aggregate/current

**Resource:** [Spectrum Analytics](../resources/Spectrum-Analytics.md)
**Get current aggregated analytics**
**Operation ID:** `spectrum-aggregate-analytics-get-current-aggregated-analytics`

Retrieves analytics aggregated from the last minute of usage on Spectrum applications underneath a given zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | spectrum-analytics_identifier | Yes |  |
| `appID` | query | spectrum-analytics_app_id_param | No |  |
| `colo_name` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get current aggregated analytics response |
| 4xx | Get current aggregated analytics response failure |

**Success Response Schema:**

[spectrum-analytics_query-response-aggregate](../schemas/spectrum-analytics/spectrum-analytics-query-response-aggregate.md)

## Security

- **api_token**
- **api_email**
- **api_key**
