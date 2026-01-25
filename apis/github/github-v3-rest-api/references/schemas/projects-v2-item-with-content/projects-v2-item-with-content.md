# projects-v2-item-with-content

An item belonging to a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The unique identifier of the project item. |
| `node_id` | string | No | The node ID of the project item. |
| `project_url` | string (uri) | No | The API URL of the project that contains this item. |
| `content_type` | [projects-v2-item-content-type](projects-v2-item-content-type.md) | Yes |  |
| `content` | object | No | The content of the item, which varies by content type. |
| `creator` | [simple-user](simple-user.md) | No |  |
| `created_at` | string (date-time) | Yes | The time when the item was created. |
| `updated_at` | string (date-time) | Yes | The time when the item was last updated. |
| `archived_at` | string (date-time) | Yes | The time when the item was archived. |
| `item_url` | string (uri) | No | The API URL of this item. |
| `fields` | object[] | No | The fields and values associated with this item. |

