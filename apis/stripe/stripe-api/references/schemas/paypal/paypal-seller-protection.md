# paypal_seller_protection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `dispute_categories` | string[] | No | An array of conditions that are covered for the transaction, if applicable. |
| `status` | enum: eligible, not_eligible, partially_eligible | Yes | Indicates whether the transaction is eligible for PayPal's seller protection. |

