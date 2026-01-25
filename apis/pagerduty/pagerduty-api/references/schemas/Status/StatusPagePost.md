# StatusPagePost

A Post represents a communication resource presented in the Status Page about certain aspects of one or more services associated.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An unique identifier within Status Page scope that defines a single Post resource. |
| `self` | string | No | The API resource URL of the Post. |
| `type` | string | No | The type of the object returned by the API - in this case, a Status Page Post. |
| `post_type` | enum: incident, maintenance | No | The type of the Post. |
| `status_page` | object | No | Status Page |
| `linked_resource` | object | No | Linked resource |
| `postmortem` | object | No | Postmortem |
| `title` | string | No | The title given to a Post. |
| `starts_at` | string (date-time) | No | The date and time the Post intent becomes effective - only for maintenance post type. |
| `ends_at` | string (date-time) | No | The date and time the Post intent is concluded - only for maintenance post type. |
| `updates` | object[] | No | List of status_page_post_update references associated to a Post. |

## Nested Fields

### `status_page`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

### `linked_resource`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Linked resource unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

### `postmortem`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Postmortem unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

