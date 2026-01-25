# GET /zones/{zone_identifier}/analytics/dashboard

**Resource:** [Zone Analytics (Deprecated)](../resources/Zone-Analytics-Deprecated.md)
**Get dashboard**
**Operation ID:** `zone-analytics-(-deprecated)-get-dashboard`
⚠️ **Deprecated**

The dashboard view provides both totals and timeseries data for the given zone and time period across the entire Cloudflare network.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_identifier` | path | zone-analytics-api_identifier | Yes |  |
| `until` | query | zone-analytics-api_until | No |  |
| `since` | query | any | No |  |
| `continuous` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get dashboard response |
| 4XX | Get dashboard response failure |

**Success Response Schema:**

[zone-analytics-api_dashboard_response](../schemas/zone-analytics-api/zone-analytics-api-dashboard-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
