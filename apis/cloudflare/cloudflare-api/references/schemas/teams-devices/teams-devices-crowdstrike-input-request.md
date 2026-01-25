# teams-devices_crowdstrike_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connection_id` | string | Yes | Posture Integration ID. |
| `last_seen` | string | No | For more details on last seen, please refer to the Crowdstrike documentation. |
| `operator` | enum: <, <=, >... | No | Operator. |
| `os` | string | No | Os Version. |
| `overall` | string | No | Overall. |
| `sensor_config` | string | No | SensorConfig. |
| `state` | enum: online, offline, unknown | No | For more details on state, please refer to the Crowdstrike documentation. |
| `version` | string | No | Version. |
| `versionOperator` | enum: <, <=, >... | No | Version Operator. |

