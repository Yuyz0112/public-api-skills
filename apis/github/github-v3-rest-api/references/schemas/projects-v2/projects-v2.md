# projects-v2

A projects v2 project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The unique identifier of the project. |
| `node_id` | string | Yes | The node ID of the project. |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `creator` | [simple-user](simple-user.md) | Yes |  |
| `title` | string | Yes | The project title. |
| `description` | string | Yes | A short description of the project. |
| `public` | boolean | Yes | Whether the project is visible to anyone with access to the owner. |
| `closed_at` | string (date-time) | Yes | The time when the project was closed. |
| `created_at` | string (date-time) | Yes | The time when the project was created. |
| `updated_at` | string (date-time) | Yes | The time when the project was last updated. |
| `number` | integer | Yes | The project number. |
| `short_description` | string | Yes | A concise summary of the project. |
| `deleted_at` | string (date-time) | Yes | The time when the project was deleted. |
| `deleted_by` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `state` | enum: open, closed | No | The current state of the project. |
| `latest_status_update` | [nullable-projects-v2-status-update](nullable-projects-v2-status-update.md) | No |  |
| `is_template` | boolean | No | Whether this project is a template |

