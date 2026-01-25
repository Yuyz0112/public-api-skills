# rum_rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | [rum_timestamp](rum-timestamp.md) | No |  |
| `host` | string | No | The hostname the rule will be applied to. |
| `id` | [rum_rule_identifier](rum-rule-identifier.md) | No |  |
| `inclusive` | boolean | No | Whether the rule includes or excludes traffic from being measured. |
| `is_paused` | boolean | No | Whether the rule is paused or not. |
| `paths` | string[] | No | The paths the rule will be applied to. |
| `priority` | number | No |  |

