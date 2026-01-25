# billing_bill_resource_invoicing_parents_invoice_subscription_parent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) defined as subscription metadata when an invoice is created. Becomes an immutable snapshot of the subscription metadata at the time of invoice finalization.
 *Note: This attribute is populated only for invoices created on or after June 29, 2023.* |
| `subscription` | any | Yes | The subscription that generated this invoice |
| `subscription_proration_date` | integer (unix-time) | No | Only set for upcoming invoices that preview prorations. The time used to calculate prorations. |

