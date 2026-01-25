# mconn_recorded_event

Recorded Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `e` | [mconn_event](mconn-event.md) | Yes |  |
| `n` | number | Yes | Sequence number, used to order events with the same timestamp |
| `t` | number | Yes | Time the Event was recorded (seconds since the Unix epoch) |

