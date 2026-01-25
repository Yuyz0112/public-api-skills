# PUT /accounts/{account_id}/rum/v2/{ruleset_id}/rule/{rule_id}

**Resource:** [Web Analytics](../resources/Web-Analytics.md)
**Update a Web Analytics rule**
**Operation ID:** `web-analytics-update-rule`

Updates a rule in a Web Analytics ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | rum_identifier | Yes |  |
| `ruleset_id` | path | rum_ruleset_identifier | Yes |  |
| `rule_id` | path | rum_rule_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [rum_create-rule-request](../schemas/rum/rum-create-rule-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Updated Web Analytics rule. |
| 4XX | Failure response. |

**Success Response Schema:**

[rum_rule-response-single](../schemas/rum/rum-rule-response-single.md)

## Security

- **api_email**
- **api_key**
- **api_token**
