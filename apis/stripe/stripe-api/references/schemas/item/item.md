# item

A line item.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_discount` | integer | Yes | Total discount amount applied. If no discounts were applied, defaults to 0. |
| `amount_subtotal` | integer | Yes | Total before any discounts or taxes are applied. |
| `amount_tax` | integer | Yes | Total tax amount applied. If no tax was applied, defaults to 0. |
| `amount_total` | integer | Yes | Total after discounts and taxes. |
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `description` | string | No | An arbitrary string attached to the object. Often useful for displaying to users. Defaults to product name. |
| `discounts` | line_items_discount_amount[] | No | The discounts applied to the line item. |
| `id` | string | Yes | Unique identifier for the object. |
| `metadata` | object | No | Set of [key-value pairs](https://docs.stripe.com/api/metadata) that you can attach to an object. This can be useful for storing additional information about the object in a structured format. |
| `object` | enum: item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `price` | any | No | The price used to generate the line item. |
| `quantity` | integer | No | The quantity of products being purchased. |
| `taxes` | line_items_tax_amount[] | No | The taxes applied to the line item. |

