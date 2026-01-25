# Account Rulesets

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/rulesets` | List account rulesets | [View](../operations/listAccountRulesets.md) |
| POST | `/accounts/{account_id}/rulesets` | Create an account ruleset | [View](../operations/createAccountRuleset.md) |
| GET | `/accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint` | Get an account entry point ruleset | [View](../operations/getAccountEntrypointRuleset.md) |
| PUT | `/accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint` | Update an account entry point ruleset | [View](../operations/updateAccountEntrypointRuleset.md) |
| GET | `/accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions` | List an account entry point ruleset's versions | [View](../operations/listAccountEntrypointRulesetVersions.md) |
| GET | `/accounts/{account_id}/rulesets/phases/{ruleset_phase}/entrypoint/versions/{ruleset_version}` | Get an account entry point ruleset version | [View](../operations/getAccountEntrypointRulesetVersion.md) |
| GET | `/accounts/{account_id}/rulesets/{ruleset_id}` | Get an account ruleset | [View](../operations/getAccountRuleset.md) |
| PUT | `/accounts/{account_id}/rulesets/{ruleset_id}` | Update an account ruleset | [View](../operations/updateAccountRuleset.md) |
| DELETE | `/accounts/{account_id}/rulesets/{ruleset_id}` | Delete an account ruleset | [View](../operations/deleteAccountRuleset.md) |
| POST | `/accounts/{account_id}/rulesets/{ruleset_id}/rules` | Create an account ruleset rule | [View](../operations/createAccountRulesetRule.md) |
| DELETE | `/accounts/{account_id}/rulesets/{ruleset_id}/rules/{rule_id}` | Delete an account ruleset rule | [View](../operations/deleteAccountRulesetRule.md) |
| PATCH | `/accounts/{account_id}/rulesets/{ruleset_id}/rules/{rule_id}` | Update an account ruleset rule | [View](../operations/updateAccountRulesetRule.md) |
| GET | `/accounts/{account_id}/rulesets/{ruleset_id}/versions` | List an account ruleset's versions | [View](../operations/listAccountRulesetVersions.md) |
| GET | `/accounts/{account_id}/rulesets/{ruleset_id}/versions/{ruleset_version}` | Get an account ruleset version | [View](../operations/getAccountRulesetVersion.md) |
| DELETE | `/accounts/{account_id}/rulesets/{ruleset_id}/versions/{ruleset_version}` | Delete an account ruleset version | [View](../operations/deleteAccountRulesetVersion.md) |
| GET | `/accounts/{account_id}/rulesets/{ruleset_id}/versions/{ruleset_version}/by_tag/{rule_tag}` | List an account ruleset version's rules by tag | [View](../operations/listAccountRulesetVersionRulesByTag.md) |
