# payment_method_paypal

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | No | Two-letter ISO code representing the buyer's country. Values are provided by PayPal directly (if supported) at the time of authorization or settlement. They cannot be set or mutated. |
| `payer_email` | string | No | Owner's email. Values are provided by PayPal directly
(if supported) at the time of authorization or settlement. They cannot be set or mutated. |
| `payer_id` | string | No | PayPal account PayerID. This identifier uniquely identifies the PayPal customer. |

