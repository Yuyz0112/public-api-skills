# DELETE /accounts/{account_id}/rulesets/{ruleset_id}/versions/{ruleset_version}

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Delete an account ruleset version**
**Operation ID:** `deleteAccountRulesetVersion`

Deletes an existing version of an account ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_version` | path | rulesets_RulesetVersion | Yes |  |
| `ruleset_id` | path | rulesets_RulesetId | Yes |  |
| `account_id` | path | rulesets_AccountId | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | (reference) |
| 4XX | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
- **api_email**
- **api_key**
