# GET /zones/{zone_id}/analytics/latency

**Resource:** [Argo Analytics for Zone](../resources/Argo-Analytics-for-Zone.md)
**Argo Analytics for a zone**
**Operation ID:** `argo-analytics-for-zone-argo-analytics-for-a-zone`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | argo-analytics_identifier | Yes |  |
| `bins` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Argo Analytics for a zone response |
| 4XX | Argo Analytics for a zone response failure |

**Success Response Schema:**

[argo-analytics_response_single](../schemas/argo-analytics/argo-analytics-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
