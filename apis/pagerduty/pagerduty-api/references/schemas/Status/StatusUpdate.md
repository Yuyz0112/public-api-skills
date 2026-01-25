# StatusUpdate

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `message` | string | No | The message of the status update. |
| `created_at` | string | No | The date/time when this status update was created. |
| `sender` | [UserReference](UserReference.md) | No |  |
| `subject` | string | No | The subject of the custom html email status update. Present if included in request body. |
| `html_message` | string | No | The html content of the custom html email status update. Present if included in request body. |

