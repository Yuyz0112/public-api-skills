# IncidentUrgencyType

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: constant, use_support_hours | No | The type of incident urgency: whether it's constant, or it's dependent on the support hours. |
| `urgency` | enum: low, high, severity_based | No | The incidents' urgency, if type is constant. |

