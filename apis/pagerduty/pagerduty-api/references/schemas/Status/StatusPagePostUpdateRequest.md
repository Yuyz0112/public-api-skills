# StatusPagePostUpdateRequest

Attributes for Post Update creation/update

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `self` | string | No | The path to which the Post Update resource is accessible. |
| `post` | object | Yes | Status Page Post |
| `message` | string | Yes | The message of the Post Update. |
| `status` | object | Yes | Status Page Status |
| `severity` | object | Yes | Status Page Severity |
| `impacted_services` | items[] | Yes | Impacted services represent the status page services affected by a post update, and its impact. |
| `update_frequency_ms` | integer | Yes | The frequency of the next Post Update in milliseconds. |
| `notify_subscribers` | boolean | Yes | Determines if the subscribers should be notified of the Post Update. |
| `reported_at` | string (date-time) | No | The date and time the Post Update was reported. |
| `type` | string | Yes | The type of the object returned by the API - in this case, a Status Page Post Update. |

## Nested Fields

### `post`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page post unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

### `status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page Status unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

### `severity`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page Severity unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

