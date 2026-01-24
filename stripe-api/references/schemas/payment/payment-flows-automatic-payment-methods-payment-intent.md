# payment_flows_automatic_payment_methods_payment_intent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allow_redirects` | enum: always, never | No | Controls whether this PaymentIntent will accept redirect-based payment methods.

Redirect-based payment methods may require your customer to be redirected to a payment method's app or site for authentication or additional steps. To [confirm](https://docs.stripe.com/api/payment_intents/confirm) this PaymentIntent, you may be required to provide a `return_url` to redirect customers back to your site after they authenticate or complete the payment. |
| `enabled` | boolean | Yes | Automatically calculates compatible payment methods |

