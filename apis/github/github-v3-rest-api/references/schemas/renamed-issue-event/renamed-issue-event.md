# renamed-issue-event

Renamed Issue Event

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
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | Yes |  |
| `rename` | object | Yes |  |

## Nested Fields

### `rename`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |
| `to` | string | Yes |  |

