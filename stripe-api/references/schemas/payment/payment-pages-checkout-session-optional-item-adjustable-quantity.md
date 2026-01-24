# payment_pages_checkout_session_optional_item_adjustable_quantity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes | Set to true if the quantity can be adjusted to any non-negative integer. |
| `maximum` | integer | No | The maximum quantity of this item the customer can purchase. By default this value is 99. You can specify a value up to 999999. |
| `minimum` | integer | No | The minimum quantity of this item the customer must purchase, if they choose to purchase it. Because this item is optional, the customer will always be able to remove it from their order, even if the `minimum` configured here is greater than 0. By default this value is 0. |

