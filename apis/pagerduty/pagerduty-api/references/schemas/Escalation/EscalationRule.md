# EscalationRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `escalation_delay_in_minutes` | integer | Yes | The number of minutes before an unacknowledged incident escalates away from this rule. |
| `targets` | EscalationTargetReference[] | Yes | The targets an incident should be assigned to upon reaching this rule. |
| `escalation_rule_assignment_strategy` | enum: round_robin, assign_to_everyone | No | The strategy used to assign the escalation rule to an incident. |

