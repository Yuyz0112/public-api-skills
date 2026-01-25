# billing_bill_resource_invoicing_lines_parents_invoice_line_item_subscription_item_parent

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `invoice_item` | string | No | The invoice item that generated this line item |
| `proration` | boolean | Yes | Whether this is a proration |
| `proration_details` | any | No | Additional details for proration line items |
| `subscription` | string | No | The subscription that the subscription item belongs to |
| `subscription_item` | string | Yes | The subscription item that generated this line item |

