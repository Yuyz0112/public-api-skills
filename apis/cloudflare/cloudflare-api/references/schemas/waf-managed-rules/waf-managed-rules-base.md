# waf-managed-rules_base

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | [waf-managed-rules_schemas-description](waf-managed-rules-schemas-description.md) | No |  |
| `group` | object | No | Defines the rule group to which the current WAF rule belongs. |
| `id` | [waf-managed-rules_rule_components-schemas-identifier](waf-managed-rules-rule-components-schemas-identifier.md) | No |  |
| `package_id` | [waf-managed-rules_identifier](waf-managed-rules-identifier.md) | No |  |
| `priority` | [waf-managed-rules_priority](waf-managed-rules-priority.md) | No |  |

## Nested Fields

### `group`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [waf-managed-rules_components-schemas-identifier](waf-managed-rules-components-schemas-identifier.md) | No |  |
| `name` | [waf-managed-rules_name](waf-managed-rules-name.md) | No |  |

