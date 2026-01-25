# GET /accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions

**Resource:** [Account Rulesets](../resources/Account-Rulesets.md)
**List an account entry point ruleset's versions**
**Operation ID:** `listAccountEntrypointRulesetVersions`

Fetches the versions of an account entry point ruleset.

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
