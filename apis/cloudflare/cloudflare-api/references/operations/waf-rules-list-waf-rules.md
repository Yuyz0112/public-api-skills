# GET /zones/{zone_id}/firewall/waf/packages/{package_id}/rules

**Resource:** [WAF rules](../resources/WAF-rules.md)
**List WAF rules**
**Operation ID:** `waf-rules-list-waf-rules`
⚠️ **Deprecated**

Fetches WAF rules in a WAF package.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_id` | path | waf-managed-rules_identifier | Yes |  |
| `zone_id` | path | waf-managed-rules_schemas-identifier | Yes |  |
| `mode` | query | enum: DIS, CHL, BLK... | No |  |
| `group_id` | query | any | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: priority, group_id, description | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |
| `description` | query | string | No |  |
| `priority` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List WAF rules response. |
| 4XX | List WAF rules response failure. |

**Success Response Schema:**

[waf-managed-rules_rule_response_collection](../schemas/waf-managed-rules/waf-managed-rules-rule-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
