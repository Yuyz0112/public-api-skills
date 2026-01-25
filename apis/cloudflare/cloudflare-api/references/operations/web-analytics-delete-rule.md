# DELETE /accounts/{account_id}/rum/v2/{ruleset_id}/rule/{rule_id}

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Delete a Web Analytics rule**
**Operation ID:** `web-analytics-delete-rule`

Deletes an existing rule from a Web Analytics ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `ruleset_id` | path | rum_ruleset_identifier | Yes |  |
| `rule_id` | path | rum_rule_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deleted Web Analytics rule identifier. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rule-id-response-single](../schemas/rum/rum-rule-id-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
