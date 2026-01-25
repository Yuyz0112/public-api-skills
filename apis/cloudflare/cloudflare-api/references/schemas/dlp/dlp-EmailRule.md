# dlp_EmailRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | [dlp_EmailRuleAction](dlp-EmailRuleAction.md) | Yes |  |
| `conditions` | dlp_EmailRuleCondition[] | Yes | Triggered if all conditions match. |
| `created_at` | string (date-time) | Yes |  |
| `description` | string | No |  |
| `enabled` | boolean | Yes |  |
| `name` | string | Yes |  |
| `priority` | integer (int32) | Yes |  |
| `rule_id` | string (uuid) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

