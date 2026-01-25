# GET /accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**Get an account entry point ruleset**
**Operation ID:** `getAccountEntrypointRuleset`

Fetches the latest version of the account entry point ruleset for a given phase.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ruleset_phase` | path | rulesets_RulesetPhase | Yes |  |
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
