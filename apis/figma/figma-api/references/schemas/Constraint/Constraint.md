# Constraint

Sizing constraint for exports.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: SCALE, WIDTH, HEIGHT | Yes | Type of constraint to apply:

- `SCALE`: Scale by `value`.
- `WIDTH`: Scale proportionally and set width to `value`.
- `HEIGHT`: Scale proportionally and set height to `value`. |
| `value` | number | Yes | See type property for effect of this field. |

