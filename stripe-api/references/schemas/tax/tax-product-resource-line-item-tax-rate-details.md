# tax_product_resource_line_item_tax_rate_details

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `display_name` | string | Yes | A localized display name for tax type, intended to be human-readable. For example, "Local Sales and Use Tax", "Value-added tax (VAT)", or "Umsatzsteuer (USt.)". |
| `percentage_decimal` | string | Yes | The tax rate percentage as a string. For example, 8.5% is represented as "8.5". |
| `tax_type` | enum: amusement_tax, communications_tax, gst... | Yes | The tax type, such as `vat` or `sales_tax`. |

