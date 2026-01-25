# GET /accounts/{account_id}/rulesets/{ruleset_id}/versions/{ruleset_version}

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Get an account ruleset version**
**Operation ID:** `getAccountRulesetVersion`

Fetches a specific version of an account ruleset.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_version` | path | rulesets_RulesetVersion | Yes |  |
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
