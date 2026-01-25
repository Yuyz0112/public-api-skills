# simple-check-suite

A suite of checks performed on the code of a given code change

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after` | string | No |  |
| `app` | [integration](integration.md) | No |  |
| `before` | string | No |  |
| `conclusion` | enum: success, failure, neutral... | No |  |
| `created_at` | string (date-time) | No |  |
| `head_branch` | string | No |  |
| `head_sha` | string | No | The SHA of the head commit that is being checked. |
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `pull_requests` | pull-request-minimal[] | No |  |
| `repository` | [minimal-repository](minimal-repository.md) | No |  |
| `status` | enum: queued, in_progress, completed... | No |  |
| `updated_at` | string (date-time) | No |  |
| `url` | string | No |  |

