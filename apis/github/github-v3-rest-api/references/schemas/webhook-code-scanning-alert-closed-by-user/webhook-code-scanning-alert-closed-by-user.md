# webhook-code-scanning-alert-closed-by-user

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: closed_by_user | Yes |  |
| `alert` | object | Yes | The code scanning alert involved in the event. |
| `commit_oid` | [webhooks_code_scanning_commit_oid](webhooks-code-scanning-commit-oid.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `ref` | [webhooks_code_scanning_ref](webhooks-code-scanning-ref.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `alert`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignees` | simple-user[] | No |  |
| `created_at` | string (date-time) | Yes | The time that the alert was created in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ.` |
| `dismissed_at` | string (date-time) | Yes | The time that the alert was dismissed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `dismissed_by` | object | Yes |  |
| `dismissed_comment` | [code-scanning-alert-dismissed-comment](code-scanning-alert-dismissed-comment.md) | No |  |
| `dismissed_reason` | enum: false positive, won't fix, used in tests... | Yes | The reason for dismissing or closing the alert. |
| `fixed_at` | any | No | The time that the alert was fixed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `html_url` | string (uri) | Yes | The GitHub URL of the alert resource. |
| `most_recent_instance` | object | No |  |
| `number` | integer | Yes | The code scanning alert number. |
| `rule` | object | Yes |  |
| `state` | enum: dismissed, fixed | Yes | State of a code scanning alert. |
| `tool` | object | Yes |  |
| `url` | string (uri) | Yes |  |
| `dismissal_approved_by` | object | No |  |

#### `alert.dismissed_by`

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

#### `alert.most_recent_instance`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `analysis_key` | string | Yes | Identifies the configuration under which the analysis was executed. For example, in GitHub Actions this includes the workflow filename and job name. |
| `category` | string | No | Identifies the configuration under which the analysis was executed. |
| `classifications` | string[] | No |  |
| `commit_sha` | string | No |  |
| `environment` | string | Yes | Identifies the variable values associated with the environment in which the analysis that generated this alert instance was performed, such as the language that was analyzed. |
| `location` | object | No |  |
| `message` | object | No |  |
| `ref` | string | Yes | The full Git reference, formatted as `refs/heads/<branch name>`. |
| `state` | enum: open, dismissed, fixed | Yes | State of a code scanning alert. |

#### `alert.rule`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | A short description of the rule used to detect the alert. |
| `full_description` | string | No |  |
| `help` | string | No |  |
| `help_uri` | string | No | A link to the documentation for the rule used to detect the alert. |
| `id` | string | Yes | A unique identifier for the rule used to detect the alert. |
| `name` | string | No |  |
| `severity` | enum: none, note, warning... | Yes | The severity of the alert. |
| `tags` | string[] | No |  |

#### `alert.tool`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `guid` | string | No |  |
| `name` | string | Yes | The name of the tool used to generate the code scanning analysis alert. |
| `version` | string | Yes | The version of the tool used to detect the alert. |

#### `alert.dismissal_approved_by`

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

