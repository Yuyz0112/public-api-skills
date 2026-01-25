# PUT /zones/{zone_id}/firewall/waf/overrides/{overrides_id}

**Resource:** [WAF overrides](../resources/WAF-overrides.md)
**Update WAF override**
**Operation ID:** `waf-overrides-update-waf-override`
⚠️ **Deprecated**

Updates an existing URI-based WAF override.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `overrides_id` | path | firewall_overrides-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update WAF override response |
| 4XX | Update WAF override response failure |

**Success Response Schema:**

[firewall_override_response_single](../schemas/firewall/firewall-override-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
