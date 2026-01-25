# commit-comment

Commit Comment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html_url` | string (uri) | Yes |  |
| `url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `body` | string | Yes |  |
| `path` | string | Yes |  |
| `position` | integer | Yes |  |
| `line` | integer | Yes |  |
| `commit_id` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

