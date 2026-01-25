# portal_flows_subscription_update_confirm_item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the [subscription item](https://docs.stripe.com/api/subscriptions/object#subscription_object-items-data-id) to be updated. |
| `price` | string | No | The price the customer should subscribe to through this flow. The price must also be included in the configuration's [`features.subscription_update.products`](https://docs.stripe.com/api/customer_portal/configuration#portal_configuration_object-features-subscription_update-products). |
| `quantity` | integer | No | [Quantity](https://docs.stripe.com/subscriptions/quantities) for this item that the customer should subscribe to through this flow. |

