# billing.meter_event_summary

A billing meter event summary represents an aggregated view of a customer's billing meter events within a specified timeframe. It indicates how much
usage was accrued by a customer for that period.

Note: Meters events are aggregated asynchronously so the meter event summaries provide an eventually consistent view of the reported usage.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aggregated_value` | number | Yes | Aggregated value of all the events within `start_time` (inclusive) and `end_time` (inclusive). The aggregation strategy is defined on meter via `default_aggregation`. |
| `end_time` | integer (unix-time) | Yes | End timestamp for this event summary (exclusive). Must be aligned with minute boundaries. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `meter` | string | Yes | The meter associated with this event summary. |
| `object` | enum: billing.meter_event_summary | Yes | String representing the object's type. Objects of the same type share the same value. |
| `start_time` | integer (unix-time) | Yes | Start timestamp for this event summary (inclusive). Must be aligned with minute boundaries. |

