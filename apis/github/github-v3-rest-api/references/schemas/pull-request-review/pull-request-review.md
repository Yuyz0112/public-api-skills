# pull-request-review

Pull Request Reviews are reviews on pull requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the review |
| `node_id` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `body` | string | Yes | The text of the review. |
| `state` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `pull_request_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |
| `submitted_at` | string (date-time) | No |  |
| `commit_id` | string | Yes | A commit SHA for the review. If the commit object was garbage collected or forcibly deleted, then it no longer exists in Git and this value will be `null`. |
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

