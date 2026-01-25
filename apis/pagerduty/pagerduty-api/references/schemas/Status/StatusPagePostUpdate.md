# StatusPagePostUpdate

An update for a Post.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | The ID of the Post Update. |
| `self` | string | No | The path to which the Post Update resource is accessible. |
| `post` | object | No | Status Page Post |
| `message` | string | No | The message of the Post Update. |
| `reviewed_status` | enum: approved, not_reviewed | No | The status of the Post Updates to retrieve. |
| `status` | object | No | Status Page Status |
| `severity` | object | No | Status Page Severity |
| `impacted_services` | object[] | No | Impacted services represent the status page services affected by a post update, and its impact. |
| `update_frequency_ms` | integer | No | The frequency of the next Post Update in milliseconds. |
| `notify_subscribers` | boolean | No | Determines if the subscribers should be notified of the Post Update. |
| `reported_at` | string (date-time) | No | The date and time the Post Update was reported. |
| `type` | string | No | The type of the object returned by the API - in this case, a Status Page Post Update. |

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

### `impacted_services`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `service` | any | No | Status Page Service |
| `impact` | any | No | Status Page Impact |

