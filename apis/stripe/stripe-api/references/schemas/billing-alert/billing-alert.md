# billing.alert

A billing alert is a resource that notifies you when a certain usage threshold on a meter is crossed. For example, you might create a billing alert to notify you when a certain user made 100 API requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `alert_type` | enum: usage_threshold | Yes | Defines the type of the alert. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.alert | Yes | String representing the object's type. Objects of the same type share the same value. |
| `status` | enum: active, archived, inactive | No | Status of the alert. This can be active, inactive or archived. |
| `title` | string | Yes | Title of the alert. |
| `usage_threshold` | any | No | Encapsulates configuration of the alert to monitor usage on a specific [Billing Meter](https://docs.stripe.com/api/billing/meter). |

