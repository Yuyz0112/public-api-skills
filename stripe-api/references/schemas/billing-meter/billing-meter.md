# billing.meter

Meters specify how to aggregate meter events over a billing period. Meter events represent the actions that customers take in your system. Meters attach to prices and form the basis of the bill.

Related guide: [Usage based billing](https://docs.stripe.com/billing/subscriptions/usage-based)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer_mapping` | [billing_meter_resource_customer_mapping_settings](billing-meter-resource-customer-mapping-settings.md) | Yes |  |
| `default_aggregation` | [billing_meter_resource_aggregation_settings](billing-meter-resource-aggregation-settings.md) | Yes |  |
| `display_name` | string | Yes | The meter's name. |
| `event_name` | string | Yes | The name of the meter event to record usage for. Corresponds with the `event_name` field on meter events. |
| `event_time_window` | enum: day, hour | No | The time window which meter events have been pre-aggregated for, if any. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.meter | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, inactive | Yes | The meter's status. |
| `status_transitions` | [billing_meter_resource_billing_meter_status_transitions](billing-meter-resource-billing-meter-status-transitions.md) | Yes |  |
| `updated` | integer (unix-time) | Yes | Time at which the object was last updated. Measured in seconds since the Unix epoch. |
| `value_settings` | [billing_meter_resource_billing_meter_value](billing-meter-resource-billing-meter-value.md) | Yes |  |

