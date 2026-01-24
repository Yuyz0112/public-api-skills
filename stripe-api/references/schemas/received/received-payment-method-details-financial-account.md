# received_payment_method_details_financial_account

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The FinancialAccount ID. |
| `network` | enum: stripe | Yes | The rails the ReceivedCredit was sent over. A FinancialAccount can only send funds over `stripe`. |

