# thread

Thread

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `subject` | object | Yes |  |
| `reason` | string | Yes |  |
| `unread` | boolean | Yes |  |
| `updated_at` | string | Yes |  |
| `last_read_at` | string | Yes |  |
| `url` | string | Yes |  |
| `subscription_url` | string | Yes |  |

## Nested Fields

### `subject`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | string | Yes |  |
| `url` | string | Yes |  |
| `latest_comment_url` | string | Yes |  |
| `type` | string | Yes |  |

