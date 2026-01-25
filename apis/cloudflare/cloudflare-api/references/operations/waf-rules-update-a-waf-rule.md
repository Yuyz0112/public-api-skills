# PATCH /zones/{zone_id}/firewall/waf/packages/{package_id}/rules/{rule_id}

**Resource:** [WAF rules](../resources/WAF-rules.md)
**Update a WAF rule**
**Operation ID:** `waf-rules-update-a-waf-rule`
⚠️ **Deprecated**

Updates a WAF rule. You can only update the mode/action of the rule.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | waf-managed-rules_identifier | Yes |  |
| `package_id` | path | waf-managed-rules_identifier | Yes |  |
| `zone_id` | path | waf-managed-rules_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a WAF rule response. |
| 4XX | Update a WAF rule response failure. |

## Security

- **api_email**
- **api_key**
- **api_token**
