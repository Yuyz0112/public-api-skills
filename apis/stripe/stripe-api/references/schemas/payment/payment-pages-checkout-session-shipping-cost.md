# payment_pages_checkout_session_shipping_cost

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_subtotal` | integer | Yes | Total shipping cost before any discounts or taxes are applied. |
| `amount_tax` | integer | Yes | Total tax amount applied due to shipping costs. If no tax was applied, defaults to 0. |
| `amount_total` | integer | Yes | Total shipping cost after discounts and taxes are applied. |
| `shipping_rate` | any | No | The ID of the ShippingRate for this order. |
| `taxes` | line_items_tax_amount[] | No | The taxes applied to the shipping rate. |

