# billing_bill_resource_invoicing_pricing_pricing

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `price_details` | [billing_bill_resource_invoicing_pricing_pricing_price_details](billing-bill-resource-invoicing-pricing-pricing-price-details.md) | No |  |
| `type` | enum: price_details | Yes | The type of the pricing details. |
| `unit_amount_decimal` | string (decimal) | No | The unit amount (in the `currency` specified) of the item which contains a decimal value with at most 12 decimal places. |

