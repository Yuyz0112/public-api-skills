# customer_balance_resource_cash_balance_transaction_resource_adjusted_for_overdraft

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `balance_transaction` | any | Yes | The [Balance Transaction](https://docs.stripe.com/api/balance_transactions/object) that corresponds to funds taken out of your Stripe balance. |
| `linked_transaction` | any | Yes | The [Cash Balance Transaction](https://docs.stripe.com/api/cash_balance_transactions/object) that brought the customer balance negative, triggering the clawback of funds. |

