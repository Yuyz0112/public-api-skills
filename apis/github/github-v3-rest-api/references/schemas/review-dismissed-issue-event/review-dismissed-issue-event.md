# review-dismissed-issue-event

Review Dismissed Issue Event

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
| `dismissed_review` | object | Yes |  |

## Nested Fields

### `dismissed_review`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `state` | string | Yes |  |
| `review_id` | integer | Yes |  |
| `dismissal_message` | string | Yes |  |
| `dismissal_commit_id` | string | No |  |

