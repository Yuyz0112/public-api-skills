# page-build

Page Build

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `status` | string | Yes |  |
| `error` | object | Yes |  |
| `pusher` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `commit` | string | Yes |  |
| `duration` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

## Nested Fields

### `error`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | Yes |  |

