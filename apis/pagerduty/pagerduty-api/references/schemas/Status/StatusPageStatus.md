# StatusPageStatus

A Status represents a level of undergoing work and/or assessment for a given Status Page post.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An unique identifier within Status Page scope that defines a Status entry. |
| `self` | string | No | The API resource URL of the Status. |
| `description` | string | No | The description is a human-readable text that describes the Status level. |
| `post_type` | enum: incident, maintenance | No | The type of the Post. |
| `status_page` | object | No | Status Page |
| `type` | string | No | The type of the object returned by the API - in this case, a Status Page Status. |

## Nested Fields

### `status_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

