# GET /zones/{zone_identifier}/analytics/colos

**Resource:** [Zone Analytics (Deprecated)](../resources/Zone-Analytics-Deprecated.md)
**Get analytics by Co-locations**
**Operation ID:** `zone-analytics-(-deprecated)-get-analytics-by-co-locations`
⚠️ **Deprecated**

This view provides a breakdown of analytics data by datacenter. Note: This is available to Enterprise customers only.

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
| 200 | Get analytics by Co-locations response |
| 4XX | Get analytics by Co-locations response failure |

**Success Response Schema:**

[zone-analytics-api_colo_response](../schemas/zone-analytics-api/zone-analytics-api-colo-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
