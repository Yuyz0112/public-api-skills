# r2_bucket-lock-rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `condition` | any | Yes |  |
| `enabled` | boolean | Yes | Whether or not this rule is in effect. |
| `id` | string | Yes | Unique identifier for this rule. |
| `prefix` | string | No | Rule will only apply to objects/uploads in the bucket that start with the given prefix, an empty prefix can be provided to scope rule to all objects/uploads. |

