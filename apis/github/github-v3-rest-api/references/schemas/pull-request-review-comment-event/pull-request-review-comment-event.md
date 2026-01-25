# pull-request-review-comment-event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes |  |
| `pull_request` | [pull-request-minimal](pull-request-minimal.md) | Yes |  |
| `comment` | object | Yes |  |

## Nested Fields

### `comment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `pull_request_review_id` | integer | Yes |  |
| `diff_hunk` | string | Yes |  |
| `path` | string | Yes |  |
| `position` | integer | Yes |  |
| `original_position` | integer | Yes |  |
| `subject_type` | string | No |  |
| `commit_id` | string | Yes |  |
| `user` | object | Yes |  |
| `body` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `pull_request_url` | string (uri) | Yes |  |
| `_links` | object | Yes |  |
| `original_commit_id` | string | Yes |  |
| `reactions` | object | Yes |  |
| `in_reply_to_id` | integer | No |  |

#### `comment.user`

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
| `id` | integer (int64) | No |  |
| `login` | string | No |  |
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

#### `comment._links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |
| `self` | object | Yes |  |

#### `comment.reactions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `+1` | integer | No |  |
| `-1` | integer | No |  |
| `confused` | integer | No |  |
| `eyes` | integer | No |  |
| `heart` | integer | No |  |
| `hooray` | integer | No |  |
| `laugh` | integer | No |  |
| `rocket` | integer | No |  |
| `total_count` | integer | No |  |
| `url` | string (uri) | No |  |

