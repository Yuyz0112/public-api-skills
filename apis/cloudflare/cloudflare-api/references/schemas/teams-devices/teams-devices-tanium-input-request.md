# teams-devices_tanium_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `connection_id` | string | Yes | Posture Integration ID. |
| `eid_last_seen` | string | No | For more details on eid last seen, refer to the Tanium documentation. |
| `operator` | enum: <, <=, >... | No | Operator to evaluate risk_level or eid_last_seen. |
| `risk_level` | enum: low, medium, high... | No | For more details on risk level, refer to the Tanium documentation. |
| `scoreOperator` | enum: <, <=, >... | No | Score Operator. |
| `total_score` | number | No | For more details on total score, refer to the Tanium documentation. |

