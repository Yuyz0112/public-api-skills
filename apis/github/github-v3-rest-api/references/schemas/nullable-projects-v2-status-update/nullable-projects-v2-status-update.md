# nullable-projects-v2-status-update

An status update belonging to a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The unique identifier of the status update. |
| `node_id` | string | Yes | The node ID of the status update. |
| `project_node_id` | string | No | The node ID of the project that this status update belongs to. |
| `creator` | [simple-user](simple-user.md) | No |  |
| `created_at` | string (date-time) | Yes | The time when the status update was created. |
| `updated_at` | string (date-time) | Yes | The time when the status update was last updated. |
| `status` | enum: INACTIVE, ON_TRACK, AT_RISK... | No | The current status. |
| `start_date` | string (date) | No | The start date of the period covered by the update. |
| `target_date` | string (date) | No | The target date associated with the update. |
| `body` | string | No | Body of the status update |

