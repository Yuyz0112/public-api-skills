# pull-request-review-event

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | string | Yes |  |
| `review` | object | Yes |  |
| `pull_request` | [pull-request-minimal](pull-request-minimal.md) | Yes |  |

## Nested Fields

### `review`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `user` | [nullable-simple-user](nullable-simple-user.md) | No |  |
| `body` | string | No |  |
| `commit_id` | string | No |  |
| `submitted_at` | string | No |  |
| `state` | string | No |  |
| `html_url` | string (uri) | No |  |
| `pull_request_url` | string (uri) | No |  |
| `_links` | object | No |  |
| `updated_at` | string | No |  |

#### `review._links`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `html` | object | Yes |  |
| `pull_request` | object | Yes |  |

