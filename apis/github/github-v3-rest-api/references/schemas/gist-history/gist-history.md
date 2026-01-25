# gist-history

Gist History

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `user` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `version` | string | No |  |
| `committed_at` | string (date-time) | No |  |
| `change_status` | object | No |  |
| `url` | string (uri) | No |  |

## Nested Fields

### `change_status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total` | integer | No |  |
| `additions` | integer | No |  |
| `deletions` | integer | No |  |

