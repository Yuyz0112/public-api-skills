# dlp_CreateEmailRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | [dlp_EmailRuleAction](dlp-EmailRuleAction.md) | Yes |  |
| `conditions` | dlp_EmailRuleCondition[] | Yes | Triggered if all conditions match. |
| `description` | string | No |  |
| `enabled` | boolean | Yes |  |
| `name` | string | Yes |  |

