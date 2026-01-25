# terminal_reader_reader_resource_set_reader_display_action

Represents a reader action to set the reader display

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cart` | any | No | Cart object to be displayed by the reader, including line items, amounts, and currency. |
| `type` | enum: cart | Yes | Type of information to be displayed by the reader. Only `cart` is currently supported. |

