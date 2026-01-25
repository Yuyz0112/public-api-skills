# teams-devices_sentinelone_s2s_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_threats` | number | No | The Number of active threats. |
| `connection_id` | string | Yes | Posture Integration ID. |
| `infected` | boolean | No | Whether device is infected. |
| `is_active` | boolean | No | Whether device is active. |
| `network_status` | enum: connected, disconnected, disconnecting... | No | Network status of device. |
| `operational_state` | enum: na, partially_disabled, auto_fully_disabled... | No | Agent operational state. |
| `operator` | enum: <, <=, >... | No | Operator. |

