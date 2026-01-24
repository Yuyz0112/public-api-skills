# portal_flows_flow_subscription_update_confirm

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `discounts` | portal_flows_subscription_update_confirm_discount[] | No | The coupon or promotion code to apply to this subscription update. |
| `items` | portal_flows_subscription_update_confirm_item[] | Yes | The [subscription item](https://docs.stripe.com/api/subscription_items) to be updated through this flow. Currently, only up to one may be specified and subscriptions with multiple items are not updatable. |
| `subscription` | string | Yes | The ID of the subscription to be updated. |

