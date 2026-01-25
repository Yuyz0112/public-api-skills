# webhook-workflow-job-queued

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: queued | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `workflow_job` | object | Yes |  |
| `deployment` | [deployment](deployment.md) | No |  |

## Nested Fields

### `workflow_job`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `check_run_url` | string (uri) | Yes |  |
| `completed_at` | string | Yes |  |
| `conclusion` | string | Yes |  |
| `created_at` | string | Yes | The time that the job created. |
| `head_sha` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `labels` | string[] | Yes |  |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |
| `run_attempt` | integer | Yes |  |
| `run_id` | number | Yes |  |
| `run_url` | string (uri) | Yes |  |
| `runner_group_id` | integer | Yes |  |
| `runner_group_name` | string | Yes |  |
| `runner_id` | integer | Yes |  |
| `runner_name` | string | Yes |  |
| `started_at` | string (date-time) | Yes |  |
| `status` | enum: queued, in_progress, completed... | Yes |  |
| `head_branch` | string | Yes | The name of the current branch. |
| `workflow_name` | string | Yes | The name of the workflow. |
| `steps` | object[] | Yes |  |
| `url` | string (uri) | Yes |  |

#### `workflow_job.steps`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `completed_at` | string | Yes |  |
| `conclusion` | enum: failure, skipped, success... | Yes |  |
| `name` | string | Yes |  |
| `number` | integer | Yes |  |
| `started_at` | string | Yes |  |
| `status` | enum: completed, in_progress, queued... | Yes |  |

