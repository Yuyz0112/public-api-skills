# gist-comment

A comment made to a gist.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `body` | string | Yes | The comment text. |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |

