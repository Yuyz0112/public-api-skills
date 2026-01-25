# GET /accounts/{account_id}/rulesets/{ruleset_id}

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Get an account ruleset**
**Operation ID:** `getAccountRuleset`

Fetches the latest version of an account ruleset.

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
