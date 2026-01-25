# projects-v2-field

A field inside a projects v2 project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier of the field. |
| `node_id` | string | No | The node ID of the field. |
| `project_url` | string | Yes | The API URL of the project that contains the field. |
| `name` | string | Yes | The name of the field. |
| `data_type` | enum: assignees, linked_pull_requests, reviewers... | Yes | The field's data type. |
| `options` | projects-v2-single-select-options[] | No | The options available for single select fields. |
| `configuration` | object | No | Configuration for iteration fields. |
| `created_at` | string (date-time) | Yes | The time when the field was created. |
| `updated_at` | string (date-time) | Yes | The time when the field was last updated. |

## Nested Fields

### `configuration`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `start_day` | integer | No | The day of the week when the iteration starts. |
| `duration` | integer | No | The duration of the iteration in days. |
| `iterations` | projects-v2-iteration-settings[] | No |  |

