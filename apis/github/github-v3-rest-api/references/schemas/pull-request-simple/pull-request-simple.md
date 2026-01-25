# pull-request-simple

Pull Request Simple

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `diff_url` | string (uri) | Yes |  |
| `patch_url` | string (uri) | Yes |  |
| `issue_url` | string (uri) | Yes |  |
| `commits_url` | string (uri) | Yes |  |
| `review_comments_url` | string (uri) | Yes |  |
| `review_comment_url` | string | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `statuses_url` | string (uri) | Yes |  |
| `number` | integer | Yes |  |
| `state` | string | Yes |  |
| `locked` | boolean | Yes |  |
| `title` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `body` | string | Yes |  |
| `labels` | object[] | Yes |  |
| `milestone` | [nullable-milestone](nullable-milestone.md) | Yes |  |
| `active_lock_reason` | string | No |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `closed_at` | string (date-time) | Yes |  |
| `merged_at` | string (date-time) | Yes |  |
| `merge_commit_sha` | string | Yes |  |
| `assignee` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `assignees` | simple-user[] | No |  |
| `requested_reviewers` | simple-user[] | No |  |
| `requested_teams` | team[] | No |  |
| `head` | object | Yes |  |
| `base` | object | Yes |  |
| `_links` | object | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `auto_merge` | [auto-merge](auto-merge.md) | Yes |  |
| `draft` | boolean | No | Indicates whether or not the pull request is a draft. |

## Nested Fields

### `labels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string | Yes |  |
| `name` | string | Yes |  |
| `description` | string | Yes |  |
| `color` | string | Yes |  |
| `default` | boolean | Yes |  |

### `head`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | [repository](repository.md) | Yes |  |
| `sha` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |

### `base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | [repository](repository.md) | Yes |  |
| `sha` | string | Yes |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |

### `_links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | [link](link.md) | Yes |  |
| `commits` | [link](link.md) | Yes |  |
| `statuses` | [link](link.md) | Yes |  |
| `html` | [link](link.md) | Yes |  |
| `issue` | [link](link.md) | Yes |  |
| `review_comments` | [link](link.md) | Yes |  |
| `review_comment` | [link](link.md) | Yes |  |
| `self` | [link](link.md) | Yes |  |

