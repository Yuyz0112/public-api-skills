# billing_credit_grants_resource_balance_credit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | [billing_credit_grants_resource_amount](billing-credit-grants-resource-amount.md) | Yes |  |
| `credits_application_invoice_voided` | any | No | Details of the invoice to which the reinstated credits were originally applied. Only present if `type` is `credits_application_invoice_voided`. |
| `type` | enum: credits_application_invoice_voided, credits_granted | Yes | The type of credit transaction. |

