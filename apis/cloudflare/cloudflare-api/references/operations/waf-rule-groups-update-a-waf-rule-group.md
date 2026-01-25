# PATCH /zones/{zone_id}/firewall/waf/packages/{package_id}/groups/{group_id}

**Resource:** [WAF rule groups](../resources/WAF-rule-groups.md)
**Update a WAF rule group**
**Operation ID:** `waf-rule-groups-update-a-waf-rule-group`
⚠️ **Deprecated**

Updates a WAF rule group. You can update the state (`mode` parameter) of a rule group.

**Note:** Applies only to the [previous version of WAF managed rules](https://developers.cloudflare.com/support/firewall/managed-rules-web-application-firewall-waf/understanding-waf-managed-rules-web-application-firewall/).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `group_id` | path | waf-managed-rules_identifier | Yes |  |
| `package_id` | path | waf-managed-rules_identifier | Yes |  |
| `zone_id` | path | waf-managed-rules_schemas-identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update a WAF rule group response. |
| 4XX | Update a WAF rule group response failure. |

**Success Response Schema:**

[waf-managed-rules_rule_group_response_single](../schemas/waf-managed-rules/waf-managed-rules-rule-group-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
