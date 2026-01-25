# account_invoices_settings

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `default_account_tax_ids` | any[] | No | The list of default Account Tax IDs to automatically include on invoices. Account Tax IDs get added when an invoice is finalized. |
| `hosted_payment_method_save` | enum: always, never, offer | No | Whether to save the payment method after a payment is completed for a one-time invoice or a subscription invoice when the customer already has a default payment method on the hosted invoice page. |

