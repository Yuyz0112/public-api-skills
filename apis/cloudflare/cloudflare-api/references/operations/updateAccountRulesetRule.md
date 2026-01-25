# PATCH /accounts/{account_id}/rulesets/{ruleset_id}/rules/{rule_id}

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Update an account ruleset rule**
**Operation ID:** `updateAccountRulesetRule`

Updates an existing rule in an account ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `rule_id` | path | rulesets_RuleId | Yes |  |
| `ruleset_id` | path | rulesets_RulesetId | Yes |  |
| `account_id` | path | rulesets_AccountId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
