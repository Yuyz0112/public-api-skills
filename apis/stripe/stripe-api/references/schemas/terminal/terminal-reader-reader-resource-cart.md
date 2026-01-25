# terminal_reader_reader_resource_cart

Represents a cart to be displayed on the reader

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `currency` | string (currency) | Yes | Three-letter [ISO currency code](https://www.iso.org/iso-4217-currency-codes.html), in lowercase. Must be a [supported currency](https://stripe.com/docs/currencies). |
| `line_items` | terminal_reader_reader_resource_line_item[] | Yes | List of line items in the cart. |
| `tax` | integer | No | Tax amount for the entire cart. A positive integer in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `total` | integer | Yes | Total amount for the entire cart, including tax. A positive integer in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |

