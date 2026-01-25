# AvailableWorkflowSystemRule

The Atlassian provided system rules available.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | The rule description. |
| `incompatibleRuleKeys` | string[] | Yes | List of rules that conflict with this one. |
| `isAvailableForInitialTransition` | boolean | Yes | Whether the rule can be added added to an initial transition. |
| `isVisible` | boolean | Yes | Whether the rule is visible. |
| `name` | string | Yes | The rule name. |
| `ruleKey` | string | Yes | The rule key. |
| `ruleType` | enum: Condition, Validator, Function... | Yes | The rule type. |

