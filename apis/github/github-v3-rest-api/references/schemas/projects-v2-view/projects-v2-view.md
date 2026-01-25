# projects-v2-view

A view inside a projects v2 project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier of the view. |
| `number` | integer | Yes | The number of the view within the project. |
| `name` | string | Yes | The name of the view. |
| `layout` | enum: table, board, roadmap | Yes | The layout of the view. |
| `node_id` | string | Yes | The node ID of the view. |
| `project_url` | string | Yes | The API URL of the project that contains the view. |
| `html_url` | string (uri) | Yes | The web URL of the view. |
| `creator` | any | Yes |  |
| `created_at` | string (date-time) | Yes | The time when the view was created. |
| `updated_at` | string (date-time) | Yes | The time when the view was last updated. |
| `filter` | string | No | The filter query for the view. |
| `visible_fields` | integer[] | Yes | The list of field IDs that are visible in the view. |
| `sort_by` | array[] | Yes | The sorting configuration for the view. Each element is a tuple of [field_id, direction] where direction is "asc" or "desc". |
| `group_by` | integer[] | Yes | The list of field IDs used for horizontal grouping. |
| `vertical_group_by` | integer[] | Yes | The list of field IDs used for vertical grouping (board layout). |

