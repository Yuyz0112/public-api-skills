# payment_links_resource_subscription_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The subscription's description, meant to be displayable to the customer. Use this field to optionally store an explanation of the subscription for rendering in Stripe surfaces and certain local payment methods UIs. |
| `invoice_settings` | [payment_links_resource_subscription_data_invoice_settings](payment-links-resource-subscription-data-invoice-settings.md) | Yes |  |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that will set metadata on [Subscriptions](https://docs.stripe.com/api/subscriptions) generated from this payment link. |
| `trial_period_days` | integer | No | Integer representing the number of trial period days before the customer is charged for the first time. |
| `trial_settings` | any | No | Settings related to subscription trials. |

