# webhook-check-suite-rerequested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: rerequested | Yes |  |
| `check_suite` | object | Yes | The [check_suite](https://docs.github.com/rest/checks/suites#get-a-check-suite). |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `check_suite`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | Yes |  |
| `app` | object | Yes | GitHub apps are a new way to extend GitHub. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks. GitHub apps are first class actors within GitHub. |
| `before` | string | Yes |  |
| `check_runs_url` | string (uri) | Yes |  |
| `conclusion` | enum: success, failure, neutral... | Yes | The summary conclusion for all check runs that are part of the check suite. This value will be `null` until the check run has completed. |
| `created_at` | string (date-time) | Yes |  |
| `head_branch` | string | Yes | The head branch name the changes are on. |
| `head_commit` | object | Yes |  |
| `head_sha` | string | Yes | The SHA of the head commit that is being checked. |
| `id` | integer | Yes |  |
| `latest_check_runs_count` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `pull_requests` | object[] | Yes | An array of pull requests that match this check suite. A pull request matches a check suite if they have the same `head_sha` and `head_branch`. When the check suite's `head_branch` is in a forked repository it will be `null` and the `pull_requests` array will be empty. |
| `rerequestable` | boolean | No |  |
| `runs_rerequestable` | boolean | No |  |
| `status` | enum: requested, in_progress, completed... | Yes | The summary status for all check runs that are part of the check suite. Can be `requested`, `in_progress`, or `completed`. |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes | URL that points to the check suite API resource. |

#### `check_suite.app`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string (date-time) | Yes |  |
| `description` | string | Yes |  |
| `events` | string[] | No | The list of events for the GitHub app |
| `external_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the GitHub app |
| `client_id` | string | No | The Client ID for the GitHub app |
| `name` | string | Yes | The name of the GitHub app |
| `node_id` | string | Yes |  |
| `owner` | object | Yes |  |
| `permissions` | object | No | The set of permissions for the GitHub app |
| `slug` | string | No | The slug name of the GitHub app |
| `updated_at` | string (date-time) | Yes |  |

#### `check_suite.head_commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | Yes | Metaproperties for Git author/committer information. |
| `committer` | object | Yes | Metaproperties for Git author/committer information. |
| `id` | string | Yes |  |
| `message` | string | Yes |  |
| `timestamp` | string | Yes |  |
| `tree_id` | string | Yes |  |

#### `check_suite.pull_requests`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `base` | object | Yes |  |
| `head` | object | Yes |  |
| `id` | integer | Yes |  |
| `number` | integer | Yes |  |
| `url` | string (uri) | Yes |  |

