# teams-devices_custom_s2s_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connection_id` | string | Yes | Posture Integration ID. |
| `operator` | enum: <, <=, >... | Yes | Operator. |
| `score` | number | Yes | A value between 0-100 assigned to devices set by the 3rd party posture provider. |

