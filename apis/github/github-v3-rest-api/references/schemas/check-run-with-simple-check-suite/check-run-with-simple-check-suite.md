# check-run-with-simple-check-suite

A check performed on the code of a given code change

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `app` | [integration](integration.md) | Yes |  |
| `check_suite` | [simple-check-suite](simple-check-suite.md) | Yes |  |
| `completed_at` | string (date-time) | Yes |  |
| `conclusion` | enum: waiting, pending, startup_failure... | Yes |  |
| `deployment` | [deployment-simple](deployment-simple.md) | No |  |
| `details_url` | string | Yes |  |
| `external_id` | string | Yes |  |
| `head_sha` | string | Yes | The SHA of the commit that is being checked. |
| `html_url` | string | Yes |  |
| `id` | integer | Yes | The id of the check. |
| `name` | string | Yes | The name of the check. |
| `node_id` | string | Yes |  |
| `output` | object | Yes |  |
| `pull_requests` | pull-request-minimal[] | Yes |  |
| `started_at` | string (date-time) | Yes |  |
| `status` | enum: queued, in_progress, completed... | Yes | The phase of the lifecycle that the check is currently in. |
| `url` | string | Yes |  |

## Nested Fields

### `output`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annotations_count` | integer | Yes |  |
| `annotations_url` | string (uri) | Yes |  |
| `summary` | string | Yes |  |
| `text` | string | Yes |  |
| `title` | string | Yes |  |

