# rum_modify-rules-request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `delete_rules` | rum_rule_identifier[] | No | A list of rule identifiers to delete. |
| `rules` | object[] | No | A list of rules to create or update. |

## Nested Fields

### `rules`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `host` | string | No |  |
| `id` | [rum_rule_identifier](rum-rule-identifier.md) | No |  |
| `inclusive` | boolean | No |  |
| `is_paused` | boolean | No |  |
| `paths` | string[] | No |  |

