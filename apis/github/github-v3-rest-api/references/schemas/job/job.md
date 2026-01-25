# job

Information of a job execution in a workflow run

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The id of the job. |
| `run_id` | integer | Yes | The id of the associated workflow run. |
| `run_url` | string | Yes |  |
| `run_attempt` | integer | No | Attempt number of the associated workflow run, 1 for first attempt and higher if the workflow was re-run. |
| `node_id` | string | Yes |  |
| `head_sha` | string | Yes | The SHA of the commit that is being run. |
| `url` | string | Yes |  |
| `html_url` | string | Yes |  |
| `status` | enum: queued, in_progress, completed... | Yes | The phase of the lifecycle that the job is currently in. |
| `conclusion` | enum: success, failure, neutral... | Yes | The outcome of the job. |
| `created_at` | string (date-time) | Yes | The time that the job created, in ISO 8601 format. |
| `started_at` | string (date-time) | Yes | The time that the job started, in ISO 8601 format. |
| `completed_at` | string (date-time) | Yes | The time that the job finished, in ISO 8601 format. |
| `name` | string | Yes | The name of the job. |
| `steps` | object[] | No | Steps in this job. |
| `check_run_url` | string | Yes |  |
| `labels` | string[] | Yes | Labels for the workflow job. Specified by the "runs_on" attribute in the action's workflow file. |
| `runner_id` | integer | Yes | The ID of the runner to which this job has been assigned. (If a runner hasn't yet been assigned, this will be null.) |
| `runner_name` | string | Yes | The name of the runner to which this job has been assigned. (If a runner hasn't yet been assigned, this will be null.) |
| `runner_group_id` | integer | Yes | The ID of the runner group to which this job has been assigned. (If a runner hasn't yet been assigned, this will be null.) |
| `runner_group_name` | string | Yes | The name of the runner group to which this job has been assigned. (If a runner hasn't yet been assigned, this will be null.) |
| `workflow_name` | string | Yes | The name of the workflow. |
| `head_branch` | string | Yes | The name of the current branch. |

## Nested Fields

### `steps`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `status` | enum: queued, in_progress, completed | Yes | The phase of the lifecycle that the job is currently in. |
| `conclusion` | string | Yes | The outcome of the job. |
| `name` | string | Yes | The name of the job. |
| `number` | integer | Yes |  |
| `started_at` | string (date-time) | No | The time that the step started, in ISO 8601 format. |
| `completed_at` | string (date-time) | No | The time that the job finished, in ISO 8601 format. |

