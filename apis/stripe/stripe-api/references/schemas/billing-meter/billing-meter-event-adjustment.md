# billing.meter_event_adjustment

A billing meter event adjustment is a resource that allows you to cancel a meter event. For example, you might create a billing meter event adjustment to cancel a meter event that was created in error or attached to the wrong customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cancel` | any | No | Specifies which event to cancel. |
| `event_name` | string | Yes | The name of the meter event. Corresponds with the `event_name` field on a meter. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.meter_event_adjustment | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: complete, pending | Yes | The meter event adjustment's status. |
| `type` | enum: cancel | Yes | Specifies whether to cancel a single event or a range of events for a time period. Time period cancellation is not supported yet. |

