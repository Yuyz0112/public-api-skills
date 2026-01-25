# zones_string_constraint

String constraint.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `operator` | enum: matches, contains, equals... | Yes | The matches operator can use asterisks and pipes as wildcard and 'or' operators. |
| `value` | string | Yes | The value to apply the operator to. |

