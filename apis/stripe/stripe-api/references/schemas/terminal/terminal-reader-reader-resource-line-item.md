# terminal_reader_reader_resource_line_item

Represents a line item to be displayed on the reader

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `amount` | integer | Yes | The amount of the line item. A positive integer in the [smallest currency unit](https://docs.stripe.com/currencies#zero-decimal). |
| `description` | string | Yes | Description of the line item. |
| `quantity` | integer | Yes | The quantity of the line item. |

