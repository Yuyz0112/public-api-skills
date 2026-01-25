# billing.meter_event

Meter events represent actions that customers take in your system. You can use meter events to bill a customer based on their usage. Meter events are associated with billing meters, which define both the contents of the event’s payload and how to aggregate those events.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `event_name` | string | Yes | The name of the meter event. Corresponds with the `event_name` field on a meter. |
| `identifier` | string | Yes | A unique identifier for the event. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.meter_event | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payload` | object | Yes | The payload of the event. This contains the fields corresponding to a meter's `customer_mapping.event_payload_key` (default is `stripe_customer_id`) and `value_settings.event_payload_key` (default is `value`). Read more about the [payload](https://docs.stripe.com/billing/subscriptions/usage-based/meters/configure#meter-configuration-attributes). |
| `timestamp` | integer (unix-time) | Yes | The timestamp passed in when creating the event. Measured in seconds since the Unix epoch. |

