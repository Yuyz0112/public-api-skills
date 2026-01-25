# timeline-comment-event

Timeline Comment Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event` | string | Yes |  |
| `actor` | [simple-user](simple-user.md) | Yes |  |
| `id` | integer | Yes | Unique identifier of the issue comment |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the issue comment |
| `body` | string | No | Contents of the issue comment |
| `body_text` | string | No |  |
| `body_html` | string | No |  |
| `html_url` | string (uri) | Yes |  |
| `user` | [simple-user](simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `issue_url` | string (uri) | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |
| `reactions` | [reaction-rollup](reaction-rollup.md) | No |  |

