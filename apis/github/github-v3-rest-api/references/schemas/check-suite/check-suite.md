# check-suite

A suite of checks performed on the code of a given code change

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `head_branch` | string | Yes |  |
| `head_sha` | string | Yes | The SHA of the head commit that is being checked. |
| `status` | enum: queued, in_progress, completed... | Yes | The phase of the lifecycle that the check suite is currently in. Statuses of waiting, requested, and pending are reserved for GitHub Actions check suites. |
| `conclusion` | enum: success, failure, neutral... | Yes |  |
| `url` | string | Yes |  |
| `before` | string | Yes |  |
| `after` | string | Yes |  |
| `pull_requests` | pull-request-minimal[] | Yes |  |
| `app` | [nullable-integration](nullable-integration.md) | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `head_commit` | [simple-commit](simple-commit.md) | Yes |  |
| `latest_check_runs_count` | integer | Yes |  |
| `check_runs_url` | string | Yes |  |
| `rerequestable` | boolean | No |  |
| `runs_rerequestable` | boolean | No |  |

