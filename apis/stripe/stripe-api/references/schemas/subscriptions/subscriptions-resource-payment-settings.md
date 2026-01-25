# subscriptions_resource_payment_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `payment_method_options` | any | No | Payment-method-specific configuration to provide to invoices created by the subscription. |
| `payment_method_types` | string[] | No | The list of payment method types to provide to every invoice created by the subscription. If not set, Stripe attempts to automatically determine the types to use by looking at the invoice’s default payment method, the subscription’s default payment method, the customer’s default payment method, and your [invoice template settings](https://dashboard.stripe.com/settings/billing/invoice). |
| `save_default_payment_method` | enum: off, on_subscription | No | Configure whether Stripe updates `subscription.default_payment_method` when payment succeeds. Defaults to `off`. |

