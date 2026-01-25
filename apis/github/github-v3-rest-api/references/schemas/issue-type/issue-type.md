# issue-type

The type of issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier of the issue type. |
| `node_id` | string | Yes | The node identifier of the issue type. |
| `name` | string | Yes | The name of the issue type. |
| `description` | string | Yes | The description of the issue type. |
| `color` | enum: gray, blue, green... | No | The color of the issue type. |
| `created_at` | string (date-time) | No | The time the issue type created. |
| `updated_at` | string (date-time) | No | The time the issue type last updated. |
| `is_enabled` | boolean | No | The enabled state of the issue type. |

