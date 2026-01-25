# Oncall

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `escalation_policy` | [EscalationPolicyReference](EscalationPolicyReference.md) | No |  |
| `user` | [UserReference](UserReference.md) | No |  |
| `schedule` | [ScheduleReference](ScheduleReference.md) | No |  |
| `escalation_level` | integer | No | The escalation level for the on-call. |
| `start` | string (date-time) | No | The start of the on-call. If `null`, the on-call is a permanent user on-call. |
| `end` | string (date-time) | No | The end of the on-call. If `null`, the user does not go off-call. |

