# webhook-code-scanning-alert-reopened-by-user

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: reopened_by_user | Yes |  |
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
| `dismissed_at` | any | Yes | The time that the alert was dismissed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `dismissed_by` | any | Yes |  |
| `dismissed_comment` | [code-scanning-alert-dismissed-comment](code-scanning-alert-dismissed-comment.md) | No |  |
| `dismissed_reason` | any | Yes | The reason for dismissing or closing the alert. Can be one of: `false positive`, `won't fix`, and `used in tests`. |
| `fixed_at` | any | No | The time that the alert was fixed in ISO 8601 format: `YYYY-MM-DDTHH:MM:SSZ`. |
| `html_url` | string (uri) | Yes | The GitHub URL of the alert resource. |
| `most_recent_instance` | object | No |  |
| `number` | integer | Yes | The code scanning alert number. |
| `rule` | object | Yes |  |
| `state` | enum: open, fixed | Yes | State of a code scanning alert. Events for alerts found outside the default branch will return a `null` value until they are dismissed or fixed. |
| `tool` | object | Yes |  |
| `url` | string (uri) | Yes |  |

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
| `id` | string | Yes | A unique identifier for the rule used to detect the alert. |
| `severity` | enum: none, note, warning... | Yes | The severity of the alert. |

#### `alert.tool`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the tool used to generate the code scanning analysis alert. |
| `version` | string | Yes | The version of the tool used to detect the alert. |

