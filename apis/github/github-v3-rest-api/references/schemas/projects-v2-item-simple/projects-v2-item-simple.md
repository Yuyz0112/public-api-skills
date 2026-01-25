# projects-v2-item-simple

An item belonging to a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The unique identifier of the project item. |
| `node_id` | string | No | The node ID of the project item. |
| `content` | any | No | The content represented by the item. |
| `content_type` | [projects-v2-item-content-type](projects-v2-item-content-type.md) | Yes |  |
| `creator` | [simple-user](simple-user.md) | No |  |
| `created_at` | string (date-time) | Yes | The time when the item was created. |
| `updated_at` | string (date-time) | Yes | The time when the item was last updated. |
| `archived_at` | string (date-time) | Yes | The time when the item was archived. |
| `project_url` | string (uri) | No | The URL of the project this item belongs to. |
| `item_url` | string (uri) | No | The URL of the item in the project. |

