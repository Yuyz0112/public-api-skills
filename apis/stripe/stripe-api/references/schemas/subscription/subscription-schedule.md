# subscription_schedule

A subscription schedule allows you to create and manage the lifecycle of a subscription by predefining expected changes.

Related guide: [Subscription schedules](https://docs.stripe.com/billing/subscriptions/subscription-schedules)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `application` | any | No | ID of the Connect Application that created the schedule. |
| `billing_mode` | [subscriptions_resource_billing_mode](subscriptions-resource-billing-mode.md) | Yes |  |
| `canceled_at` | integer (unix-time) | No | Time at which the subscription schedule was canceled. Measured in seconds since the Unix epoch. |
| `completed_at` | integer (unix-time) | No | Time at which the subscription schedule was completed. Measured in seconds since the Unix epoch. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `current_phase` | any | No | Object representing the start and end dates for the current phase of the subscription schedule, if it is `active`. |
| `customer` | any | Yes | ID of the customer who owns the subscription schedule. |
| `customer_account` | string | No | ID of the account who owns the subscription schedule. |
| `default_settings` | [subscription_schedules_resource_default_settings](subscription-schedules-resource-default-settings.md) | Yes |  |
| `end_behavior` | enum: cancel, none, release... | Yes | Behavior of the subscription schedule and underlying subscription when it ends. Possible values are `release` or `cancel` with the default being `release`. `release` will end the subscription schedule and keep the underlying subscription running. `cancel` will end the subscription schedule and cancel the underlying subscription. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: subscription_schedule | Yes | String representing the object's type. Objects of the same type share the same value. |
| `phases` | subscription_schedule_phase_configuration[] | Yes | Configuration for the subscription schedule's phases. |
| `released_at` | integer (unix-time) | No | Time at which the subscription schedule was released. Measured in seconds since the Unix epoch. |
| `released_subscription` | string | No | ID of the subscription once managed by the subscription schedule (if it is released). |
| `status` | enum: active, canceled, completed... | Yes | The present status of the subscription schedule. Possible values are `not_started`, `active`, `completed`, `released`, and `canceled`. You can read more about the different states in our [behavior guide](https://docs.stripe.com/billing/subscriptions/subscription-schedules). |
| `subscription` | any | No | ID of the subscription managed by the subscription schedule. |
| `test_clock` | any | No | ID of the test clock this subscription schedule belongs to. |

