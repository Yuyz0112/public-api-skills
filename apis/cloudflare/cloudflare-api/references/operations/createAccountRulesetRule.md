# POST /accounts/{account_id}/rulesets/{ruleset_id}/rules

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Create an account ruleset rule**
**Operation ID:** `createAccountRulesetRule`

Adds a new rule to an account ruleset. The rule will be added to the end of the existing list of rules in the ruleset by default.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
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
