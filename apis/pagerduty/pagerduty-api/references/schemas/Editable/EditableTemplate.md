# EditableTemplate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `template_type` | enum: status_update | No | The type of template (`status_update` is the only supported template at this time) |
| `name` | string | No | The name of the template |
| `description` | string | No | Description of the template |
| `templated_fields` | object | No |  |

## Nested Fields

### `templated_fields`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `email_subject` | string | No | The subject of the e-mail |
| `email_body` | string | No | The HTML body of the e-mail message |
| `message` | string | No | The short-message of the template (SMS, Push notification, Slack,
etc) |

