# subscriptions_resource_billing_mode

The billing mode of the subscription.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `flexible` | any | No | Configure behavior for flexible billing mode |
| `type` | enum: classic, flexible | Yes | Controls how prorations and invoices for subscriptions are calculated and orchestrated. |
| `updated_at` | integer (unix-time) | No | Details on when the current billing_mode was adopted. |

