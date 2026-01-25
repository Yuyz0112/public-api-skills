# discussion

A Discussion in a repository.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_lock_reason` | string | Yes |  |
| `answer_chosen_at` | string | Yes |  |
| `answer_chosen_by` | object | Yes |  |
| `answer_html_url` | string | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | No | How the author is associated with the repository. |
| `body` | string | Yes |  |
| `category` | object | Yes |  |
| `comments` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `locked` | boolean | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `reactions` | object | No |  |
| `repository_url` | string | Yes |  |
| `state` | enum: open, closed, locked... | Yes | The current state of the discussion.
`converting` means that the discussion is being converted from an issue.
`transferring` means that the discussion is being transferred from another repository. |
| `state_reason` | enum: resolved, outdated, duplicate... | Yes | The reason for the current state |
| `timeline_url` | string | No |  |
| `title` | string | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `user` | object | Yes |  |
| `labels` | label[] | No |  |

## Nested Fields

### `answer_chosen_by`

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
| `id` | integer | Yes |  |
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

### `category`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes |  |
| `description` | string | Yes |  |
| `emoji` | string | Yes |  |
| `id` | integer | Yes |  |
| `is_answerable` | boolean | Yes |  |
| `name` | string | Yes |  |
| `node_id` | string | No |  |
| `repository_id` | integer | Yes |  |
| `slug` | string | Yes |  |
| `updated_at` | string | Yes |  |

### `reactions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `+1` | integer | Yes |  |
| `-1` | integer | Yes |  |
| `confused` | integer | Yes |  |
| `eyes` | integer | Yes |  |
| `heart` | integer | Yes |  |
| `hooray` | integer | Yes |  |
| `laugh` | integer | Yes |  |
| `rocket` | integer | Yes |  |
| `total_count` | integer | Yes |  |
| `url` | string (uri) | Yes |  |

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

