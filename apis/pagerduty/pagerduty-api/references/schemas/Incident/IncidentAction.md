# IncidentAction

An incident action is a pending change to an incident that will automatically happen at some future time.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: unacknowledge, escalate, resolve... | Yes |  |
| `at` | string (date-time) | Yes |  |
| `to` | enum: high | No | The urgency that the incident will change to. This field is only present when the type is `urgency_change`. |

