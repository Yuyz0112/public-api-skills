# PATCH /zones/{zone_id}/settings/rum

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Toggle RUM on/off for a zone**
**Operation ID:** `web-analytics-toggle-rum`

Toggles RUM on/off for an existing zone.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | rum_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [rum_toggle-rum-request](../schemas/rum/rum-toggle-rum-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Rum toggled on/off for an existing zone. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rum-site-response-single](../schemas/rum/rum-rum-site-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
