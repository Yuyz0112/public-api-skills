# ResponderRequestTargetReference

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | string | No | The type of target (either a user or an escalation policy) |
| `id` | string | No | The id of the user or escalation policy |
| `summary` | string | No |  |
| `incident_responders` | IncidentsRespondersReference[] | No | An array of responders associated with the specified incident |

