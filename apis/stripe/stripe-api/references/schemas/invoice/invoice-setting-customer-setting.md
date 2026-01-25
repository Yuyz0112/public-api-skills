# invoice_setting_customer_setting

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `custom_fields` | invoice_setting_custom_field[] | No | Default custom fields to be displayed on invoices for this customer. |
| `default_payment_method` | any | No | ID of a payment method that's attached to the customer, to be used as the customer's default payment method for subscriptions and invoices. |
| `footer` | string | No | Default footer to be displayed on invoices for this customer. |
| `rendering_options` | any | No | Default options for invoice PDF rendering for this customer. |

