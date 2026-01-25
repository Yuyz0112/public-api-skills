# timeline-reviewed-event

Timeline Reviewed Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `event` | string | Yes |  |
| `id` | integer | Yes | Unique identifier of the review |
| `node_id` | string | Yes |  |
| `user` | [simple-user](simple-user.md) | Yes |  |
| `body` | string | Yes | The text of the review. |
| `state` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `pull_request_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |
| `submitted_at` | string (date-time) | No |  |
| `updated_at` | string (date-time) | No |  |
| `commit_id` | string | Yes | A commit SHA for the review. |
| `body_html` | string | No |  |
| `body_text` | string | No |  |
| `author_association` | [author-association](author-association.md) | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string | Yes |  |

#### `_links.pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string | Yes |  |

