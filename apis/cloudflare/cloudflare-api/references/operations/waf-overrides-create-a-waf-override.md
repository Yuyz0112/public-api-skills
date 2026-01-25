# POST /zones/{zone_id}/firewall/waf/overrides

**Resource:** [WAF overrides](../resources/WAF-overrides.md)
**Create a WAF override**
**Operation ID:** `waf-overrides-create-a-waf-override`
⚠️ **Deprecated**

Creates a URI-based WAF override for a zone.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create a WAF override response |
| 4XX | Create a WAF override response failure |

**Success Response Schema:**

[firewall_override_response_single](../schemas/firewall/firewall-override-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
