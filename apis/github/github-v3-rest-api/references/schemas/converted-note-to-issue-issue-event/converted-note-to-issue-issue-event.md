# converted-note-to-issue-issue-event

Converted Note to Issue Issue Event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `url` | string | Yes |  |
| `actor` | [simple-user](simple-user.md) | Yes |  |
| `event` | string | Yes |  |
| `commit_id` | string | Yes |  |
| `commit_url` | string | Yes |  |
| `created_at` | string | Yes |  |
| `performed_via_github_app` | [integration](integration.md) | Yes |  |
| `project_card` | object | No |  |

## Nested Fields

### `project_card`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `url` | string (uri) | Yes |  |
| `project_id` | integer | Yes |  |
| `project_url` | string (uri) | Yes |  |
| `column_name` | string | Yes |  |
| `previous_column_name` | string | No |  |

