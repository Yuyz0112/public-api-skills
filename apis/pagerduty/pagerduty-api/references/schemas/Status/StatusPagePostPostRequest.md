# StatusPagePostPostRequest

Request schema for creating/updating a given Status Page Post resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: status_page_post | Yes | The type of the object returned by the API - in this case, a Status Page Post. |
| `title` | string | Yes | The title given to a Post. |
| `post_type` | enum: incident, maintenance | Yes | The type of the Post. |
| `starts_at` | string (date-time) | Yes | The date and time the Post intent becomes effective - only for maintenance post type. |
| `ends_at` | string (date-time) | Yes | The date and time the Post intent is concluded - only for maintenance post type. |
| `updates` | StatusPagePostUpdateRequest[] | Yes | Post Updates to be associated with a Post |
| `status_page` | object | Yes | Status Page |

## Nested Fields

### `status_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

