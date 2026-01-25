# source_order_item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | No | The amount (price) for this order item. |
| `currency` | string | No | This currency of this order item. Required when `amount` is present. |
| `description` | string | No | Human-readable description for this order item. |
| `parent` | string | No | The ID of the associated object for this line item. Expandable if not null (e.g., expandable to a SKU). |
| `quantity` | integer | No | The quantity of this order item. When type is `sku`, this is the number of instances of the SKU to be ordered. |
| `type` | string | No | The type of this order item. Must be `sku`, `tax`, or `shipping`. |

