# billing.credit_grant

A credit grant is an API resource that documents the allocation of some billing credits to a customer.

Related guide: [Billing credits](https://docs.stripe.com/billing/subscriptions/usage-based/billing-credits)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | [billing_credit_grants_resource_amount](billing-credit-grants-resource-amount.md) | Yes |  |
| `applicability_config` | [billing_credit_grants_resource_applicability_config](billing-credit-grants-resource-applicability-config.md) | Yes |  |
| `category` | enum: paid, promotional | Yes | The category of this credit grant. This is for tracking purposes and isn't displayed to the customer. |
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `customer` | any | Yes | ID of the customer receiving the billing credits. |
| `customer_account` | string | No | ID of the account representing the customer receiving the billing credits |
| `effective_at` | integer (unix-time) | No | The time when the billing credits become effective-when they're eligible for use. |
| `expires_at` | integer (unix-time) | No | The time when the billing credits expire. If not present, the billing credits don't expire. |
| `id` | string | Yes | Unique identifier for the object. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `metadata` | object | Yes | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `name` | string | No | A descriptive name shown in dashboard. |
| `object` | enum: billing.credit_grant | Yes | String representing the object's type. Objects of the same type share the same value. |
| `priority` | integer | No | The priority for applying this credit grant. The highest priority is 0 and the lowest is 100. |
| `test_clock` | any | No | ID of the test clock this credit grant belongs to. |
| `updated` | integer (unix-time) | Yes | Time at which the object was last updated. Measured in seconds since the Unix epoch. |
| `voided_at` | integer (unix-time) | No | The time when this credit grant was voided. If not present, the credit grant hasn't been voided. |

