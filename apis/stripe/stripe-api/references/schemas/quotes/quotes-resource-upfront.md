# quotes_resource_upfront

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount_subtotal` | integer | Yes | Total before any discounts or taxes are applied. |
| `amount_total` | integer | Yes | Total after discounts and taxes are applied. |
| `line_items` | object | No | The line items that will appear on the next invoice after this quote is accepted. This does not include pending invoice items that exist on the customer but may still be included in the next invoice. |
| `total_details` | [quotes_resource_total_details](quotes-resource-total-details.md) | Yes |  |

## Nested Fields

### `line_items`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `data` | item[] | Yes | Details about each object. |
| `has_more` | boolean | Yes | True if this list has another page of items after this one that can be fetched. |
| `object` | enum: list | Yes | String representing the object's type. Objects of the same type share the same value. Always has the value `list`. |
| `url` | string | Yes | The URL where this list can be accessed. |

