# webhook-deployment-review-requested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: requested | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `environment` | string | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `requestor` | [webhooks_user](webhooks-user.md) | Yes |  |
| `reviewers` | object[] | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `since` | string | Yes |  |
| `workflow_job_run` | object | Yes |  |
| `workflow_run` | object | Yes |  |

## Nested Fields

### `reviewers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `reviewer` | object | No |  |
| `type` | enum: User, Team | No |  |

#### `reviewers.reviewer`

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

### `workflow_job_run`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conclusion` | any | Yes |  |
| `created_at` | string | Yes |  |
| `environment` | string | Yes |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes |  |
| `status` | string | Yes |  |
| `updated_at` | string | Yes |  |

### `workflow_run`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actor` | object | Yes |  |
| `artifacts_url` | string | No |  |
| `cancel_url` | string | No |  |
| `check_suite_id` | integer | Yes |  |
| `check_suite_node_id` | string | Yes |  |
| `check_suite_url` | string | No |  |
| `conclusion` | enum: success, failure, neutral... | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `event` | string | Yes |  |
| `head_branch` | string | Yes |  |
| `head_commit` | object | No |  |
| `head_repository` | object | No |  |
| `head_sha` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `jobs_url` | string | No |  |
| `logs_url` | string | No |  |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |
| `path` | string | Yes |  |
| `previous_attempt_url` | string | No |  |
| `pull_requests` | object[] | Yes |  |
| `referenced_workflows` | object[] | No |  |
| `repository` | object | No |  |
| `rerun_url` | string | No |  |
| `run_attempt` | integer | Yes |  |
| `run_number` | integer | Yes |  |
| `run_started_at` | string (date-time) | Yes |  |
| `status` | enum: requested, in_progress, completed... | Yes |  |
| `triggering_actor` | object | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |
| `workflow_id` | integer | Yes |  |
| `workflow_url` | string | No |  |
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

#### `workflow_run.head_repository`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archive_url` | string | No |  |
| `assignees_url` | string | No |  |
| `blobs_url` | string | No |  |
| `branches_url` | string | No |  |
| `collaborators_url` | string | No |  |
| `comments_url` | string | No |  |
| `commits_url` | string | No |  |
| `compare_url` | string | No |  |
| `contents_url` | string | No |  |
| `contributors_url` | string | No |  |
| `deployments_url` | string | No |  |
| `description` | string | No |  |
| `downloads_url` | string | No |  |
| `events_url` | string | No |  |
| `fork` | boolean | No |  |
| `forks_url` | string | No |  |
| `full_name` | string | No |  |
| `git_commits_url` | string | No |  |
| `git_refs_url` | string | No |  |
| `git_tags_url` | string | No |  |
| `hooks_url` | string | No |  |
| `html_url` | string | No |  |
| `id` | integer | No |  |
| `issue_comment_url` | string | No |  |
| `issue_events_url` | string | No |  |
| `issues_url` | string | No |  |
| `keys_url` | string | No |  |
| `labels_url` | string | No |  |
| `languages_url` | string | No |  |
| `merges_url` | string | No |  |
| `milestones_url` | string | No |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `notifications_url` | string | No |  |
| `owner` | object | No |  |
| `private` | boolean | No |  |
| `pulls_url` | string | No |  |
| `releases_url` | string | No |  |
| `stargazers_url` | string | No |  |
| `statuses_url` | string | No |  |
| `subscribers_url` | string | No |  |
| `subscription_url` | string | No |  |
| `tags_url` | string | No |  |
| `teams_url` | string | No |  |
| `trees_url` | string | No |  |
| `url` | string | No |  |

#### `workflow_run.pull_requests`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `base` | object | Yes |  |
| `head` | object | Yes |  |
| `id` | integer | Yes |  |
| `number` | integer | Yes |  |
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
| `archive_url` | string | No |  |
| `assignees_url` | string | No |  |
| `blobs_url` | string | No |  |
| `branches_url` | string | No |  |
| `collaborators_url` | string | No |  |
| `comments_url` | string | No |  |
| `commits_url` | string | No |  |
| `compare_url` | string | No |  |
| `contents_url` | string | No |  |
| `contributors_url` | string | No |  |
| `deployments_url` | string | No |  |
| `description` | string | No |  |
| `downloads_url` | string | No |  |
| `events_url` | string | No |  |
| `fork` | boolean | No |  |
| `forks_url` | string | No |  |
| `full_name` | string | No |  |
| `git_commits_url` | string | No |  |
| `git_refs_url` | string | No |  |
| `git_tags_url` | string | No |  |
| `hooks_url` | string | No |  |
| `html_url` | string | No |  |
| `id` | integer | No |  |
| `issue_comment_url` | string | No |  |
| `issue_events_url` | string | No |  |
| `issues_url` | string | No |  |
| `keys_url` | string | No |  |
| `labels_url` | string | No |  |
| `languages_url` | string | No |  |
| `merges_url` | string | No |  |
| `milestones_url` | string | No |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `notifications_url` | string | No |  |
| `owner` | object | No |  |
| `private` | boolean | No |  |
| `pulls_url` | string | No |  |
| `releases_url` | string | No |  |
| `stargazers_url` | string | No |  |
| `statuses_url` | string | No |  |
| `subscribers_url` | string | No |  |
| `subscription_url` | string | No |  |
| `tags_url` | string | No |  |
| `teams_url` | string | No |  |
| `trees_url` | string | No |  |
| `url` | string | No |  |

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

