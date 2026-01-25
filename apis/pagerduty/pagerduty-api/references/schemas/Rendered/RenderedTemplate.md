# RenderedTemplate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `templated_fields` | object | No |  |
| `warnings` | object | No | List of render warnings messages for each rendered field.
(Ex:  ["{{incident.invalid_field}} does not exist."]) |
| `errors` | string[] | No | List of errors |

## Nested Fields

### `templated_fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email_subject` | string | No | The rendered e-mail subject |
| `email_body` | string | No | The rendered e-mail body |
| `message` | string | No | The rendered short message (SMS, Push, Slack, etc) |

### `warnings`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email_subject` | string[] | No | List of warnings for email_subject |
| `email_body` | string[] | No | List of warnings for email_body |
| `message` | string[] | No | List of warnings for message field |

