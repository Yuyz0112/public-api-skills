# GET /zones/{zone_id}/firewall/waf/overrides

**Resource:** [WAF overrides](../resources/WAF-overrides.md)
**List WAF overrides**
**Operation ID:** `waf-overrides-list-waf-overrides`
⚠️ **Deprecated**

Fetches the URI-based WAF overrides in a zone.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | firewall_identifier | Yes |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List WAF overrides response |
| 4XX | List WAF overrides response failure |

**Success Response Schema:**

[firewall_override_response_collection](../schemas/firewall/firewall-override-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
