# check-run

A check performed on the code of a given code change

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | The id of the check. |
| `head_sha` | string | Yes | The SHA of the commit that is being checked. |
| `node_id` | string | Yes |  |
| `external_id` | string | Yes |  |
| `url` | string | Yes |  |
| `html_url` | string | Yes |  |
| `details_url` | string | Yes |  |
| `status` | enum: queued, in_progress, completed... | Yes | The phase of the lifecycle that the check is currently in. Statuses of waiting, requested, and pending are reserved for GitHub Actions check runs. |
| `conclusion` | enum: success, failure, neutral... | Yes |  |
| `started_at` | string (date-time) | Yes |  |
| `completed_at` | string (date-time) | Yes |  |
| `output` | object | Yes |  |
| `name` | string | Yes | The name of the check. |
| `check_suite` | object | Yes |  |
| `app` | [nullable-integration](nullable-integration.md) | Yes |  |
| `pull_requests` | pull-request-minimal[] | Yes | Pull requests that are open with a `head_sha` or `head_branch` that matches the check. The returned pull requests do not necessarily indicate pull requests that triggered the check. |
| `deployment` | [deployment-simple](deployment-simple.md) | No |  |

## Nested Fields

### `output`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `title` | string | Yes |  |
| `summary` | string | Yes |  |
| `text` | string | Yes |  |
| `annotations_count` | integer | Yes |  |
| `annotations_url` | string (uri) | Yes |  |

### `check_suite`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |

