# GET /zones/{zone_id}/analytics/latency/colos

**Resource:** [Argo Analytics for Geolocation](../resources/Argo-Analytics-for-Geolocation.md)
**Argo Analytics for a zone at different PoPs**
**Operation ID:** `argo-analytics-for-geolocation-argo-analytics-for-a-zone-at-different-po-ps`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | argo-analytics_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Argo Analytics for a zone at different PoPs response |
| 4XX | Argo Analytics for a zone at different PoPs response failure |

**Success Response Schema:**

[argo-analytics_response_single](../schemas/argo-analytics/argo-analytics-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
