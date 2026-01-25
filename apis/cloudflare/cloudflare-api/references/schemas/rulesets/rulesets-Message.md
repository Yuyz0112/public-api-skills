# rulesets_Message

A message.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | integer | No | A unique code for this message. |
| `message` | string | Yes | A text description of this message. |
| `source` | object | No | The source of this message. |

## Nested Fields

### `source`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pointer` | string | Yes | A JSON pointer to the field that is the source of the message. |

