# rulesets_Rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | [rulesets_RuleAction](rulesets-RuleAction.md) | No |  |
| `action_parameters` | object | No | The parameters configuring the rule's action. |
| `categories` | [rulesets_RuleCategories](rulesets-RuleCategories.md) | No |  |
| `description` | string | No | An informative description of the rule. |
| `enabled` | any | No |  |
| `exposed_credential_check` | [rulesets_RuleExposedCredentialCheck](rulesets-RuleExposedCredentialCheck.md) | No |  |
| `expression` | string | No | The expression defining which traffic will match the rule. |
| `id` | [rulesets_RuleId](rulesets-RuleId.md) | No |  |
| `last_updated` | string (date-time) | Yes | The timestamp of when the rule was last modified. |
| `logging` | [rulesets_RuleLogging](rulesets-RuleLogging.md) | No |  |
| `ratelimit` | [rulesets_RuleRatelimit](rulesets-RuleRatelimit.md) | No |  |
| `ref` | string | No | The reference of the rule (the rule's ID by default). |
| `version` | string | Yes | The version of the rule. |

