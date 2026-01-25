# ConditionGroupUpdate

The conditions group associated with the transition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditionGroups` | ConditionGroupUpdate[] | No | The nested conditions of the condition group. |
| `conditions` | WorkflowRuleConfiguration[] | No | The rules for this condition. |
| `operation` | enum: ANY, ALL | Yes | Determines how the conditions in the group are evaluated. Accepts either `ANY` or `ALL`. If `ANY` is used, at least one condition in the group must be true for the group to evaluate to true. If `ALL` is used, all conditions in the group must be true for the group to evaluate to true. |

