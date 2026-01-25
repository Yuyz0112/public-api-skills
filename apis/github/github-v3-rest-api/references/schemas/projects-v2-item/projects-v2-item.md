# projects-v2-item

An item belonging to a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The unique identifier of the project item. |
| `node_id` | string | No | The node ID of the project item. |
| `project_node_id` | string | No | The node ID of the project that contains this item. |
| `content_node_id` | string | Yes | The node ID of the content represented by this item. |
| `content_type` | [projects-v2-item-content-type](projects-v2-item-content-type.md) | Yes |  |
| `creator` | [simple-user](simple-user.md) | No |  |
| `created_at` | string (date-time) | Yes | The time when the item was created. |
| `updated_at` | string (date-time) | Yes | The time when the item was last updated. |
| `archived_at` | string (date-time) | Yes | The time when the item was archived. |

