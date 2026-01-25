# pending-deployment

Details of a deployment that is waiting for protection rules to pass

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environment` | object | Yes |  |
| `wait_timer` | integer | Yes | The set duration of the wait timer |
| `wait_timer_started_at` | string (date-time) | Yes | The time that the wait timer began. |
| `current_user_can_approve` | boolean | Yes | Whether the currently authenticated user can approve the deployment |
| `reviewers` | object[] | Yes | The people or teams that may approve jobs that reference the environment. You can list up to six users or teams as reviewers. The reviewers must have at least read access to the repository. Only one of the required reviewers needs to approve the job for it to proceed. |

## Nested Fields

### `environment`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | No | The id of the environment. |
| `node_id` | string | No |  |
| `name` | string | No | The name of the environment. |
| `url` | string | No |  |
| `html_url` | string | No |  |

### `reviewers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [deployment-reviewer-type](deployment-reviewer-type.md) | No |  |
| `reviewer` | any | No |  |

