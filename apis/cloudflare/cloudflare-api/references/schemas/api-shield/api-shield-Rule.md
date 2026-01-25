# api-shield_Rule

A Token Validation rule that can enforce security policies using JWT Tokens.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | [api-shield_action](api-shield-action.md) | Yes |  |
| `created_at` | [api-shield_schemas-timestamp](api-shield-schemas-timestamp.md) | No |  |
| `description` | [api-shield_schemas-description](api-shield-schemas-description.md) | Yes |  |
| `enabled` | [api-shield_enabled](api-shield-enabled.md) | Yes |  |
| `expression` | [api-shield_expression](api-shield-expression.md) | Yes |  |
| `id` | [api-shield_schemas-uuid](api-shield-schemas-uuid.md) | No |  |
| `last_updated` | [api-shield_schemas-timestamp](api-shield-schemas-timestamp.md) | No |  |
| `selector` | [api-shield_selector](api-shield-selector.md) | Yes |  |
| `title` | [api-shield_schemas-title](api-shield-schemas-title.md) | Yes |  |

