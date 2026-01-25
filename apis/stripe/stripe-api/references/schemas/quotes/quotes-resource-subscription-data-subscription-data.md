# quotes_resource_subscription_data_subscription_data

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_mode` | [quotes_resource_subscription_data_billing_mode](quotes-resource-subscription-data-billing-mode.md) | Yes |  |
| `description` | string | No | The subscription's description, meant to be displayable to the customer. Use this field to optionally store an explanation of the subscription for rendering in Stripe surfaces and certain local payment methods UIs. |
| `effective_date` | integer (unix-time) | No | When creating a new subscription, the date of which the subscription schedule will start after the quote is accepted. This date is ignored if it is in the past when the quote is accepted. Measured in seconds since the Unix epoch. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that will set metadata on the subscription or subscription schedule when the quote is accepted. If a recurring price is included in `line_items`, this field will be passed to the resulting subscription's `metadata` field. If `subscription_data.effective_date` is used, this field will be passed to the resulting subscription schedule's `phases.metadata` field. Unlike object-level metadata, this field is declarative. Updates will clear prior values. |
| `trial_period_days` | integer | No | Integer representing the number of trial period days before the customer is charged for the first time. |

