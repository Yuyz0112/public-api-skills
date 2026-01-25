# billing_credit_grants_resource_balance_debit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | [billing_credit_grants_resource_amount](billing-credit-grants-resource-amount.md) | Yes |  |
| `credits_applied` | any | No | Details of how the billing credits were applied to an invoice. Only present if `type` is `credits_applied`. |
| `type` | enum: credits_applied, credits_expired, credits_voided | Yes | The type of debit transaction. |

