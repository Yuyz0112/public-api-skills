# mconn_event_metadata

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `a` | number | Yes | Time the Event was collected (seconds since the Unix epoch) |
| `k` | string | Yes | Kind |
| `n` | number | Yes | Sequence number, used to order events with the same timestamp |
| `t` | number | Yes | Time the Event was recorded (seconds since the Unix epoch) |

