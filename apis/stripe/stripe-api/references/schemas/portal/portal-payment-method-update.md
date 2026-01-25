# portal_payment_method_update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Whether the feature is enabled. |
| `payment_method_configuration` | string | No | The [Payment Method Configuration](/api/payment_method_configurations) to use for this portal session. When specified, customers will be able to update their payment method to one of the options specified by the payment method configuration. If not set, the default payment method configuration is used. |

