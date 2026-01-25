# portal_subscription_update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billing_cycle_anchor` | enum: now, unchanged | No | Determines the value to use for the billing cycle anchor on subscription updates. Valid values are `now` or `unchanged`, and the default value is `unchanged`. Setting the value to `now` resets the subscription's billing cycle anchor to the current time (in UTC). For more information, see the billing cycle [documentation](https://docs.stripe.com/billing/subscriptions/billing-cycle). |
| `default_allowed_updates` | string[] | Yes | The types of subscription updates that are supported for items listed in the `products` attribute. When empty, subscriptions are not updateable. |
| `enabled` | boolean | Yes | Whether the feature is enabled. |
| `products` | portal_subscription_update_product[] | No | The list of up to 10 products that support subscription updates. |
| `proration_behavior` | enum: always_invoice, create_prorations, none | Yes | Determines how to handle prorations resulting from subscription updates. Valid values are `none`, `create_prorations`, and `always_invoice`. Defaults to a value of `none` if you don't set it during creation. |
| `schedule_at_period_end` | [portal_resource_schedule_update_at_period_end](portal-resource-schedule-update-at-period-end.md) | Yes |  |
| `trial_update_behavior` | enum: continue_trial, end_trial | Yes | Determines how handle updates to trialing subscriptions. Valid values are `end_trial` and `continue_trial`. Defaults to a value of `end_trial` if you don't set it during creation. |

