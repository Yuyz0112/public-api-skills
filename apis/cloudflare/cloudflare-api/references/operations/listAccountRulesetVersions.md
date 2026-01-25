# GET /accounts/{account_id}/rulesets/{ruleset_id}/versions

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**List an account ruleset's versions**
**Operation ID:** `listAccountRulesetVersions`

Fetches the versions of an account ruleset.

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
