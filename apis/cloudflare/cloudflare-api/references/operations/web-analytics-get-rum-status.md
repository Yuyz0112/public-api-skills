# GET /zones/{zone_id}/settings/rum

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Get RUM status for a zone**
**Operation ID:** `web-analytics-get-rum-status`

Retrieves RUM status for a zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | rum_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rum Status. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rum-site-response-single](../schemas/rum/rum-rum-site-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
