# billing.credit_balance_summary

Indicates the billing credit balance for billing credits granted to a customer.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `balances` | credit_balance[] | Yes | The billing credit balances. One entry per credit grant currency. If a customer only has credit grants in a single currency, then this will have a single balance entry. |
| `customer` | any | Yes | The customer the balance is for. |
| `customer_account` | string | No | The account the balance is for. |
| `livemode` | boolean | Yes | Has the value `true` if the object exists in live mode or the value `false` if the object exists in test mode. |
| `object` | enum: billing.credit_balance_summary | Yes | String representing the object's type. Objects of the same type share the same value. |

