# invoices_resource_pretax_credit_amount

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount, in cents (or local equivalent), of the pretax credit amount. |
| `credit_balance_transaction` | any | No | The credit balance transaction that was applied to get this pretax credit amount. |
| `discount` | any | No | The discount that was applied to get this pretax credit amount. |
| `type` | enum: credit_balance_transaction, discount | Yes | Type of the pretax credit amount referenced. |

