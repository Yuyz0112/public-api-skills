# webhook-status

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `branches` | object[] | Yes | An array of branch objects containing the status' SHA. Each branch contains the given SHA, but the SHA may or may not be the head of the branch. The array includes a maximum of 10 branches. |
| `commit` | object | Yes |  |
| `context` | string | Yes |  |
| `created_at` | string | Yes |  |
| `description` | string | Yes | The optional human-readable description added to the status. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `id` | integer | Yes | The unique identifier of the status. |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `name` | string | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `sha` | string | Yes | The Commit SHA. |
| `state` | enum: pending, success, failure... | Yes | The new state. Can be `pending`, `success`, `failure`, or `error`. |
| `target_url` | string | Yes | The optional link added to the status. |
| `updated_at` | string | Yes |  |

## Nested Fields

### `branches`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `commit` | object | Yes |  |
| `name` | string | Yes |  |
| `protected` | boolean | Yes |  |

#### `branches.commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

### `commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | Yes |  |
| `comments_url` | string (uri) | Yes |  |
| `commit` | object | Yes |  |
| `committer` | object | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `node_id` | string | Yes |  |
| `parents` | object[] | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

#### `commit.author`

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
| `id` | integer | No |  |
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

#### `commit.commit`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | any | Yes |  |
| `comment_count` | integer | Yes |  |
| `committer` | any | Yes |  |
| `message` | string | Yes |  |
| `tree` | object | Yes |  |
| `url` | string (uri) | Yes |  |
| `verification` | object | Yes |  |

#### `commit.committer`

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
| `id` | integer | No |  |
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

#### `commit.parents`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html_url` | string (uri) | Yes |  |
| `sha` | string | Yes |  |
| `url` | string (uri) | Yes |  |

