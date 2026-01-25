# workflow-run

An invocation of a workflow

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the workflow run. |
| `name` | string | No | The name of the workflow run. |
| `node_id` | string | Yes |  |
| `check_suite_id` | integer | No | The ID of the associated check suite. |
| `check_suite_node_id` | string | No | The node ID of the associated check suite. |
| `head_branch` | string | Yes |  |
| `head_sha` | string | Yes | The SHA of the head commit that points to the version of the workflow being run. |
| `path` | string | Yes | The full path of the workflow |
| `run_number` | integer | Yes | The auto incrementing run number for the workflow run. |
| `run_attempt` | integer | No | Attempt number of the run, 1 for first attempt and higher if the workflow was re-run. |
| `referenced_workflows` | referenced-workflow[] | No |  |
| `event` | string | Yes |  |
| `status` | string | Yes |  |
| `conclusion` | string | Yes |  |
| `workflow_id` | integer | Yes | The ID of the parent workflow. |
| `url` | string | Yes | The URL to the workflow run. |
| `html_url` | string | Yes |  |
| `pull_requests` | pull-request-minimal[] | Yes | Pull requests that are open with a `head_sha` or `head_branch` that matches the workflow run. The returned pull requests do not necessarily indicate pull requests that triggered the run. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `actor` | [simple-user](simple-user.md) | No |  |
| `triggering_actor` | [simple-user](simple-user.md) | No |  |
| `run_started_at` | string (date-time) | No | The start time of the latest run. Resets on re-run. |
| `jobs_url` | string | Yes | The URL to the jobs for the workflow run. |
| `logs_url` | string | Yes | The URL to download the logs for the workflow run. |
| `check_suite_url` | string | Yes | The URL to the associated check suite. |
| `artifacts_url` | string | Yes | The URL to the artifacts for the workflow run. |
| `cancel_url` | string | Yes | The URL to cancel the workflow run. |
| `rerun_url` | string | Yes | The URL to rerun the workflow run. |
| `previous_attempt_url` | string | No | The URL to the previous attempted run of this workflow, if one exists. |
| `workflow_url` | string | Yes | The URL to the workflow. |
| `head_commit` | [nullable-simple-commit](nullable-simple-commit.md) | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `head_repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `head_repository_id` | integer | No |  |
| `display_title` | string | Yes | The event-specific title associated with the run or the run-name if set, or the value of `run-name` if it is set in the workflow. |

