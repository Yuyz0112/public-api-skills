# ScheduledAction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: urgency_change | Yes | The type of schedule action. Must be set to urgency_change. |
| `at` | object | Yes | Represents when scheduled action will occur. |
| `to_urgency` | enum: high | Yes | Urgency level. Must be set to high. |

## Nested Fields

### `at`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: named_time | Yes | Must be set to named_time. |
| `name` | enum: support_hours_start, support_hours_end | Yes | Designates either the start or the end of support hours. |

