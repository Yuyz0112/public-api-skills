# GET /zones/{zone_id}/firewall/waf/packages/{package_id}/groups

**Resource:** [WAF rule groups](../resources/WAF-rule-groups.md)
**List WAF rule groups**
**Operation ID:** `waf-rule-groups-list-waf-rule-groups`
⚠️ **Deprecated**

Fetches the WAF rule groups in a WAF package.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_id` | path | waf-managed-rules_identifier | Yes |  |
| `zone_id` | path | waf-managed-rules_schemas-identifier | Yes |  |
| `mode` | query | any | No |  |
| `page` | query | number | No |  |
| `per_page` | query | number | No |  |
| `order` | query | enum: mode, rules_count | No |  |
| `direction` | query | enum: asc, desc | No |  |
| `match` | query | enum: any, all | No |  |
| `name` | query | string | No |  |
| `rules_count` | query | number | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Defines the list WAF rule groups response. |
| 4XX | Defines the list WAF rule groups response failure. |

**Success Response Schema:**

[waf-managed-rules_rule_group_response_collection](../schemas/waf-managed-rules/waf-managed-rules-rule-group-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
