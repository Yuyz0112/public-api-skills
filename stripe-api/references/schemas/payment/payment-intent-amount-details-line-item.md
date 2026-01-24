# payment_intent_amount_details_line_item

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `discount_amount` | integer | No | The discount applied on this line item represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). An integer greater than 0.

This field is mutually exclusive with the `amount_details[discount_amount]` field. |
| `id` | string | Yes | Unique identifier for the object. |
| `object` | enum: payment_intent_amount_details_line_item | Yes | String representing the object's type. Objects of the same type share the same value. |
| `payment_method_options` | any | No | Payment method-specific information for line items. |
| `product_code` | string | No | The product code of the line item, such as an SKU. Required for L3 rates. At most 12 characters long. |
| `product_name` | string | Yes | The product name of the line item. Required for L3 rates. At most 1024 characters long.

For Cards, this field is truncated to 26 alphanumeric characters before being sent to the card networks. For Paypal, this field is truncated to 127 characters. |
| `quantity` | integer | Yes | The quantity of items. Required for L3 rates. An integer greater than 0. |
| `tax` | any | No | Contains information about the tax on the item. |
| `unit_cost` | integer | Yes | The unit cost of the line item represented in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). Required for L3 rates. An integer greater than or equal to 0. |
| `unit_of_measure` | string | No | A unit of measure for the line item, such as gallons, feet, meters, etc. Required for L3 rates. At most 12 alphanumeric characters long. |

