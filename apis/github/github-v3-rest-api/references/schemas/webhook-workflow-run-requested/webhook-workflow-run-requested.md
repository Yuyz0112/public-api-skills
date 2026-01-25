# webhook-workflow-run-requested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: requested | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `workflow` | [webhooks_workflow](webhooks-workflow.md) | Yes |  |
| `workflow_run` | object | Yes |  |

## Nested Fields

### `workflow_run`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actor` | object | Yes |  |
| `artifacts_url` | string (uri) | Yes |  |
| `cancel_url` | string (uri) | Yes |  |
| `check_suite_id` | integer | Yes |  |
| `check_suite_node_id` | string | Yes |  |
| `check_suite_url` | string (uri) | Yes |  |
| `conclusion` | enum: success, failure, neutral... | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `event` | string | Yes |  |
| `head_branch` | string | Yes |  |
| `head_commit` | object | Yes |  |
| `head_repository` | object | Yes |  |
| `head_sha` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `jobs_url` | string (uri) | Yes |  |
| `logs_url` | string (uri) | Yes |  |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |
| `path` | string | Yes |  |
| `previous_attempt_url` | string (uri) | Yes |  |
| `pull_requests` | object[] | Yes |  |
| `referenced_workflows` | object[] | No |  |
| `repository` | object | Yes |  |
| `rerun_url` | string (uri) | Yes |  |
| `run_attempt` | integer | Yes |  |
| `run_number` | integer | Yes |  |
| `run_started_at` | string (date-time) | Yes |  |
| `status` | enum: requested, in_progress, completed... | Yes |  |
| `triggering_actor` | object | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `workflow_id` | integer | Yes |  |
| `workflow_url` | string (uri) | Yes |  |
| `display_title` | string | Yes |  |

#### `workflow_run.actor`

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

#### `workflow_run.head_commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | Yes | Metaproperties for Git author/committer information. |
| `committer` | object | Yes | Metaproperties for Git author/committer information. |
| `id` | string | Yes |  |
| `message` | string | Yes |  |
| `timestamp` | string | Yes |  |
| `tree_id` | string | Yes |  |

#### `workflow_run.head_repository`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archive_url` | string (uri-template) | Yes |  |
| `assignees_url` | string (uri-template) | Yes |  |
| `blobs_url` | string (uri-template) | Yes |  |
| `branches_url` | string (uri-template) | Yes |  |
| `collaborators_url` | string (uri-template) | Yes |  |
| `comments_url` | string (uri-template) | Yes |  |
| `commits_url` | string (uri-template) | Yes |  |
| `compare_url` | string (uri-template) | Yes |  |
| `contents_url` | string (uri-template) | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `deployments_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `downloads_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `fork` | boolean | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `full_name` | string | Yes |  |
| `git_commits_url` | string (uri-template) | Yes |  |
| `git_refs_url` | string (uri-template) | Yes |  |
| `git_tags_url` | string (uri-template) | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the repository |
| `issue_comment_url` | string (uri-template) | Yes |  |
| `issue_events_url` | string (uri-template) | Yes |  |
| `issues_url` | string (uri-template) | Yes |  |
| `keys_url` | string (uri-template) | Yes |  |
| `labels_url` | string (uri-template) | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `merges_url` | string (uri) | Yes |  |
| `milestones_url` | string (uri-template) | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `node_id` | string | Yes |  |
| `notifications_url` | string (uri-template) | Yes |  |
| `owner` | object | Yes |  |
| `private` | boolean | Yes | Whether the repository is private or public. |
| `pulls_url` | string (uri-template) | Yes |  |
| `releases_url` | string (uri-template) | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string (uri-template) | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `trees_url` | string (uri-template) | Yes |  |
| `url` | string (uri) | Yes |  |

#### `workflow_run.pull_requests`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `base` | object | Yes |  |
| `head` | object | Yes |  |
| `id` | number | Yes |  |
| `number` | number | Yes |  |
| `url` | string (uri) | Yes |  |

#### `workflow_run.referenced_workflows`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `path` | string | Yes |  |
| `ref` | string | No |  |
| `sha` | string | Yes |  |

#### `workflow_run.repository`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archive_url` | string (uri-template) | Yes |  |
| `assignees_url` | string (uri-template) | Yes |  |
| `blobs_url` | string (uri-template) | Yes |  |
| `branches_url` | string (uri-template) | Yes |  |
| `collaborators_url` | string (uri-template) | Yes |  |
| `comments_url` | string (uri-template) | Yes |  |
| `commits_url` | string (uri-template) | Yes |  |
| `compare_url` | string (uri-template) | Yes |  |
| `contents_url` | string (uri-template) | Yes |  |
| `contributors_url` | string (uri) | Yes |  |
| `deployments_url` | string (uri) | Yes |  |
| `description` | string | Yes |  |
| `downloads_url` | string (uri) | Yes |  |
| `events_url` | string (uri) | Yes |  |
| `fork` | boolean | Yes |  |
| `forks_url` | string (uri) | Yes |  |
| `full_name` | string | Yes |  |
| `git_commits_url` | string (uri-template) | Yes |  |
| `git_refs_url` | string (uri-template) | Yes |  |
| `git_tags_url` | string (uri-template) | Yes |  |
| `hooks_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the repository |
| `issue_comment_url` | string (uri-template) | Yes |  |
| `issue_events_url` | string (uri-template) | Yes |  |
| `issues_url` | string (uri-template) | Yes |  |
| `keys_url` | string (uri-template) | Yes |  |
| `labels_url` | string (uri-template) | Yes |  |
| `languages_url` | string (uri) | Yes |  |
| `merges_url` | string (uri) | Yes |  |
| `milestones_url` | string (uri-template) | Yes |  |
| `name` | string | Yes | The name of the repository. |
| `node_id` | string | Yes |  |
| `notifications_url` | string (uri-template) | Yes |  |
| `owner` | object | Yes |  |
| `private` | boolean | Yes | Whether the repository is private or public. |
| `pulls_url` | string (uri-template) | Yes |  |
| `releases_url` | string (uri-template) | Yes |  |
| `stargazers_url` | string (uri) | Yes |  |
| `statuses_url` | string (uri-template) | Yes |  |
| `subscribers_url` | string (uri) | Yes |  |
| `subscription_url` | string (uri) | Yes |  |
| `tags_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `trees_url` | string (uri-template) | Yes |  |
| `url` | string (uri) | Yes |  |

#### `workflow_run.triggering_actor`

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

