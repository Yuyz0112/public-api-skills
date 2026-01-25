# GET /zones/{zone_id}/firewall/waf/packages/{package_id}/rules/{rule_id}

**Resource:** [WAF rules](../resources/WAF-rules.md)
**Get a WAF rule**
**Operation ID:** `waf-rules-get-a-waf-rule`
⚠️ **Deprecated**

Fetches the details of a WAF rule in a WAF package.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | waf-managed-rules_identifier | Yes |  |
| `package_id` | path | waf-managed-rules_identifier | Yes |  |
| `zone_id` | path | waf-managed-rules_schemas-identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a WAF rule response. |
| 4XX | Get a WAF rule response failure. |

**Success Response Schema:**

[waf-managed-rules_rule_response_single](../schemas/waf-managed-rules/waf-managed-rules-rule-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
