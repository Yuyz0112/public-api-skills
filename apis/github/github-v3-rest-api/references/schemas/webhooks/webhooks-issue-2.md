# webhooks_issue_2

The [issue](https://docs.github.com/rest/issues/issues#get-an-issue) itself.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `active_lock_reason` | enum: resolved, off-topic, too heated... | Yes |  |
| `assignee` | object | No |  |
| `assignees` | object[] | Yes |  |
| `author_association` | enum: COLLABORATOR, CONTRIBUTOR, FIRST_TIMER... | Yes | How the author is associated with the repository. |
| `body` | string | Yes | Contents of the issue |
| `closed_at` | string (date-time) | Yes |  |
| `comments` | integer | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `draft` | boolean | No |  |
| `events_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `labels` | object[] | No |  |
| `labels_url` | string (uri-template) | Yes |  |
| `locked` | boolean | No |  |
| `milestone` | object | Yes | A collection of related issues and pull requests. |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `performed_via_github_app` | object | No | GitHub apps are a new way to extend GitHub. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks. GitHub apps are first class actors within GitHub. |
| `pull_request` | object | No |  |
| `reactions` | object | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `sub_issues_summary` | [sub-issues-summary](sub-issues-summary.md) | No |  |
| `issue_dependencies_summary` | [issue-dependencies-summary](issue-dependencies-summary.md) | No |  |
| `issue_field_values` | issue-field-value[] | No |  |
| `state` | enum: open, closed | No | State of the issue; either 'open' or 'closed' |
| `state_reason` | string | No |  |
| `timeline_url` | string (uri) | No |  |
| `title` | string | Yes | Title of the issue |
| `type` | [issue-type](issue-type.md) | No |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes | URL for the issue |
| `user` | object | Yes |  |

## Nested Fields

### `assignee`

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

### `assignees`

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

### `labels`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | string | Yes | 6-character hex code, without the leading #, identifying the color |
| `default` | boolean | Yes |  |
| `description` | string | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes | The name of the label. |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the label |

### `milestone`

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

#### `milestone.creator`

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

### `performed_via_github_app`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes |  |
| `description` | string | Yes |  |
| `events` | string[] | No | The list of events for the GitHub app |
| `external_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the GitHub app |
| `name` | string | Yes | The name of the GitHub app |
| `node_id` | string | Yes |  |
| `owner` | object | Yes |  |
| `permissions` | object | No | The set of permissions for the GitHub app |
| `slug` | string | No | The slug name of the GitHub app |
| `updated_at` | string (date-time) | Yes |  |

#### `performed_via_github_app.owner`

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

#### `performed_via_github_app.permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | enum: read, write | No |  |
| `administration` | enum: read, write | No |  |
| `checks` | enum: read, write | No |  |
| `content_references` | enum: read, write | No |  |
| `contents` | enum: read, write | No |  |
| `deployments` | enum: read, write | No |  |
| `discussions` | enum: read, write | No |  |
| `emails` | enum: read, write | No |  |
| `environments` | enum: read, write | No |  |
| `issues` | enum: read, write | No |  |
| `keys` | enum: read, write | No |  |
| `members` | enum: read, write | No |  |
| `metadata` | enum: read, write | No |  |
| `organization_administration` | enum: read, write | No |  |
| `organization_hooks` | enum: read, write | No |  |
| `organization_packages` | enum: read, write | No |  |
| `organization_plan` | enum: read, write | No |  |
| `organization_projects` | enum: read, write | No |  |
| `organization_secrets` | enum: read, write | No |  |
| `organization_self_hosted_runners` | enum: read, write | No |  |
| `organization_user_blocking` | enum: read, write | No |  |
| `packages` | enum: read, write | No |  |
| `pages` | enum: read, write | No |  |
| `pull_requests` | enum: read, write | No |  |
| `repository_hooks` | enum: read, write | No |  |
| `repository_projects` | enum: read, write | No |  |
| `secret_scanning_alerts` | enum: read, write | No |  |
| `secrets` | enum: read, write | No |  |
| `security_events` | enum: read, write | No |  |
| `security_scanning_alert` | enum: read, write | No |  |
| `single_file` | enum: read, write | No |  |
| `statuses` | enum: read, write | No |  |
| `team_discussions` | enum: read, write | No |  |
| `vulnerability_alerts` | enum: read, write | No |  |
| `workflows` | enum: read, write | No |  |

### `pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `diff_url` | string (uri) | No |  |
| `html_url` | string (uri) | No |  |
| `merged_at` | string (date-time) | No |  |
| `patch_url` | string (uri) | No |  |
| `url` | string (uri) | No |  |

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

