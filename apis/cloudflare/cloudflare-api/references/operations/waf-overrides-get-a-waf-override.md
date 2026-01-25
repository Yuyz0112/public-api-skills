# GET /zones/{zone_id}/firewall/waf/overrides/{overrides_id}

**Resource:** [WAF overrides](../resources/WAF-overrides.md)
**Get a WAF override**
**Operation ID:** `waf-overrides-get-a-waf-override`
⚠️ **Deprecated**

Fetches the details of a URI-based WAF override.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `overrides_id` | path | firewall_overrides-id | Yes |  |
| `zone_id` | path | firewall_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a WAF override response |
| 4XX | Get a WAF override response failure |

**Success Response Schema:**

[firewall_override_response_single](../schemas/firewall/firewall-override-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
