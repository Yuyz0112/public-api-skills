# issue-comment

Comments provide a way for people to collaborate on an issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the issue comment |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the issue comment |
| `body` | string | No | Contents of the issue comment |
| `body_text` | string | No |  |
| `body_html` | string | No |  |
| `html_url` | string (uri) | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `issue_url` | string (uri) | Yes |  |
| `author_association` | [author-association](author-association.md) | No |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

