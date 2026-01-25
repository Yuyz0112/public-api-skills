# commit-comment-event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes |  |
| `comment` | object | Yes |  |

## Nested Fields

### `comment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html_url` | string (uri) | No |  |
| `url` | string (uri) | No |  |
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `body` | string | No |  |
| `path` | string | No |  |
| `position` | integer | No |  |
| `line` | integer | No |  |
| `commit_id` | string | No |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `created_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

