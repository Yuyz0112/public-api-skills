# pull-request

Pull requests let you tell others about changes you've pushed to a repository on GitHub. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

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
| `number` | integer | Yes | Number uniquely identifying the pull request within its repository. |
| `state` | enum: open, closed | Yes | State of this Pull Request. Either `open` or `closed`. |
| `locked` | boolean | Yes |  |
| `title` | string | Yes | The title of the pull request. |
| `user` | [simple-user](simple-user.md) | Yes |  |
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
| `requested_teams` | team-simple[] | No |  |
| `head` | object | Yes |  |
| `base` | object | Yes |  |
| `_links` | object | Yes |  |
| `author_association` | [author-association](author-association.md) | Yes |  |
| `auto_merge` | [auto-merge](auto-merge.md) | Yes |  |
| `draft` | boolean | No | Indicates whether or not the pull request is a draft. |
| `merged` | boolean | Yes |  |
| `mergeable` | boolean | Yes |  |
| `rebaseable` | boolean | No |  |
| `mergeable_state` | string | Yes |  |
| `merged_by` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `comments` | integer | Yes |  |
| `review_comments` | integer | Yes |  |
| `maintainer_can_modify` | boolean | Yes | Indicates whether maintainers can modify the pull request. |
| `commits` | integer | Yes |  |
| `additions` | integer | Yes |  |
| `deletions` | integer | Yes |  |
| `changed_files` | integer | Yes |  |

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
| `user` | [simple-user](simple-user.md) | Yes |  |

### `base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | [repository](repository.md) | Yes |  |
| `sha` | string | Yes |  |
| `user` | [simple-user](simple-user.md) | Yes |  |

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

