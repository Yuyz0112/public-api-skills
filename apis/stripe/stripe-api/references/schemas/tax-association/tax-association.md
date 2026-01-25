# tax.association

A Tax Association exposes the Tax Transactions that Stripe attempted to create on your behalf based on the PaymentIntent input

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `calculation` | string | Yes | The [Tax Calculation](https://docs.stripe.com/api/tax/calculations/object) that was included in PaymentIntent. |
| `id` | string | Yes | Unique identifier for the object. |
| `object` | enum: tax.association | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payment_intent` | string | Yes | The [PaymentIntent](https://docs.stripe.com/api/payment_intents/object) that this Tax Association is tracking. |
| `tax_transaction_attempts` | tax_product_resource_tax_association_transaction_attempts[] | No | Information about the tax transactions linked to this payment intent |

