# webhooks_review

The review that was affected.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_links` | object | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | The text of the review. |
| `commit_id` | string | Yes | A commit SHA for the review. |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the review |
| `node_id` | string | Yes |  |
| `pull_request_url` | string (uri) | Yes |  |
| `state` | string | Yes |  |
| `submitted_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | No |  |
| `user` | object | Yes |  |

## Nested Fields

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |

#### `_links.html`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

#### `_links.pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `href` | string (uri-template) | Yes |  |

### `user`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer (int64) | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

