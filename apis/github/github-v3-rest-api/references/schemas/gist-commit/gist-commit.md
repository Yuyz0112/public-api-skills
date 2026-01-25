# gist-commit

Gist Commit

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `version` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `change_status` | object | Yes |  |
| `committed_at` | string (date-time) | Yes |  |

## Nested Fields

### `change_status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `total` | integer | No |  |
| `additions` | integer | No |  |
| `deletions` | integer | No |  |

