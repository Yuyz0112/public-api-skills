# UserSession

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `user_id` | string | Yes |  |
| `created_at` | string (date-time) | Yes | The date/time the user session was first created. |
| `type` | enum: browser, oauth | Yes | The type of the session |
| `summary` | string | Yes | The summary of the session |

