# thresholds_resource_usage_threshold_config

The usage threshold alert configuration enables setting up alerts for when a certain usage threshold on a specific meter is crossed.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `filters` | thresholds_resource_usage_alert_filter[] | No | The filters allow limiting the scope of this usage alert. You can only specify up to one filter at this time. |
| `gte` | integer | Yes | The value at which this alert will trigger. |
| `meter` | any | Yes | The [Billing Meter](/api/billing/meter) ID whose usage is monitored. |
| `recurrence` | enum: one_time | Yes | Defines how the alert will behave. |

