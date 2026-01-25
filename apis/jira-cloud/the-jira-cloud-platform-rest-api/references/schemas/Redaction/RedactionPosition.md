# RedactionPosition

Represents the position of the redaction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `adfPointer` | string | No | The ADF pointer indicating the position of the text to be redacted. This is only required when redacting from rich text(ADF) fields. For plain text fields, this field can be omitted. |
| `expectedText` | string | Yes | The text which will be redacted, encoded using SHA256 hash and Base64 digest |
| `from` | integer (int32) | Yes | The start index(inclusive) for the redaction in specified content |
| `to` | integer (int32) | Yes | The ending index(exclusive) for the redaction in specified content |

