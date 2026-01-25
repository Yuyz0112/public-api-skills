# ConditionGroupPayload

The payload for creating a condition group in a workflow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditionGroup` | ConditionGroupPayload[] | No | The nested conditions of the condition group. |
| `conditions` | RulePayload[] | No | The rules for this condition. |
| `operation` | enum: ANY, ALL | No | Determines how the conditions in the group are evaluated. Accepts either `ANY` or `ALL`. If `ANY` is used, at least one condition in the group must be true for the group to evaluate to true. If `ALL` is used, all conditions in the group must be true for the group to evaluate to true. |

