# webhook-pull-request-review-comment-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | [webhooks_changes](webhooks-changes.md) | Yes |  |
| `comment` | [webhooks_review_comment](webhooks-review-comment.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pull_request` | object | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `_links` | object | Yes |  |
| `active_lock_reason` | enum: resolved, off-topic, too heated... | Yes |  |
| `assignee` | object | Yes |  |
| `assignees` | object[] | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `auto_merge` | object | No | The status of auto merging a pull request. |
| `base` | object | Yes |  |
| `body` | string | Yes |  |
| `closed_at` | string | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `commits_url` | string (uri) | Yes |  |
| `created_at` | string | Yes |  |
| `diff_url` | string (uri) | Yes |  |
| `draft` | boolean | No |  |
| `head` | object | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `issue_url` | string (uri) | Yes |  |
| `labels` | object[] | Yes |  |
| `locked` | boolean | Yes |  |
| `merge_commit_sha` | string | Yes |  |
| `merged_at` | string | Yes |  |
| `milestone` | object | Yes | A collection of related issues and pull requests. |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `patch_url` | string (uri) | Yes |  |
| `requested_reviewers` | any[] | Yes |  |
| `requested_teams` | object[] | Yes |  |
| `review_comment_url` | string (uri-template) | Yes |  |
| `review_comments_url` | string (uri) | Yes |  |
| `state` | enum: open, closed | Yes |  |
| `statuses_url` | string (uri) | Yes |  |
| `title` | string | Yes |  |
| `updated_at` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `user` | object | Yes |  |

#### `pull_request._links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `comments` | object | Yes |  |
| `commits` | object | Yes |  |
| `html` | object | Yes |  |
| `issue` | object | Yes |  |
| `review_comment` | object | Yes |  |
| `review_comments` | object | Yes |  |
| `self` | object | Yes |  |
| `statuses` | object | Yes |  |

#### `pull_request.assignee`

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

#### `pull_request.assignees`

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

#### `pull_request.auto_merge`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `commit_message` | string | Yes | Commit message for the merge commit. |
| `commit_title` | string | Yes | Title for the merge commit message. |
| `enabled_by` | object | Yes |  |
| `merge_method` | enum: merge, squash, rebase | Yes | The merge method to use. |

#### `pull_request.base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | object | Yes | A git repository |
| `sha` | string | Yes |  |
| `user` | object | Yes |  |

#### `pull_request.head`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `label` | string | Yes |  |
| `ref` | string | Yes |  |
| `repo` | object | Yes | A git repository |
| `sha` | string | Yes |  |
| `user` | object | Yes |  |

#### `pull_request.labels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | string | Yes | 6-character hex code, without the leading #, identifying the color |
| `default` | boolean | Yes |  |
| `description` | string | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes | The name of the label. |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the label |

#### `pull_request.milestone`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `closed_at` | string (date-time) | Yes |  |
| `closed_issues` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `creator` | object | Yes |  |
| `description` | string | Yes |  |
| `due_on` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `labels_url` | string (uri) | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes | The number of the milestone. |
| `open_issues` | integer | Yes |  |
| `state` | enum: open, closed | Yes | The state of the milestone. |
| `title` | string | Yes | The title of the milestone. |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |

#### `pull_request.requested_teams`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deleted` | boolean | No |  |
| `description` | string | No | Description of the team |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes | Unique identifier of the team |
| `members_url` | string (uri-template) | No |  |
| `name` | string | Yes | Name of the team |
| `node_id` | string | No |  |
| `parent` | object | No |  |
| `permission` | string | No | Permission that the team will have for its repositories |
| `privacy` | enum: open, closed, secret | No |  |
| `repositories_url` | string (uri) | No |  |
| `slug` | string | No |  |
| `url` | string (uri) | No | URL for the team |

#### `pull_request.user`

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
| `type` | enum: Bot, User, Organization... | No |  |
| `user_view_type` | string | No |  |
| `url` | string (uri) | No |  |

