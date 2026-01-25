# terminal_reader_reader_resource_input

Represents an input to be collected using the reader

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `custom_text` | any | No | Default text of input being collected. |
| `email` | [terminal_reader_reader_resource_email](terminal-reader-reader-resource-email.md) | No |  |
| `numeric` | [terminal_reader_reader_resource_numeric](terminal-reader-reader-resource-numeric.md) | No |  |
| `phone` | [terminal_reader_reader_resource_phone](terminal-reader-reader-resource-phone.md) | No |  |
| `required` | boolean | No | Indicate that this input is required, disabling the skip button. |
| `selection` | [terminal_reader_reader_resource_selection](terminal-reader-reader-resource-selection.md) | No |  |
| `signature` | [terminal_reader_reader_resource_signature](terminal-reader-reader-resource-signature.md) | No |  |
| `skipped` | boolean | No | Indicate that this input was skipped by the user. |
| `text` | [terminal_reader_reader_resource_text](terminal-reader-reader-resource-text.md) | No |  |
| `toggles` | terminal_reader_reader_resource_toggle[] | No | List of toggles being collected. Values are present if collection is complete. |
| `type` | enum: email, numeric, phone... | Yes | Type of input being collected. |

