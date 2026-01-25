# milestone

A collection of related issues and pull requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `labels_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes | The number of the milestone. |
| `state` | enum: open, closed | Yes | The state of the milestone. |
| `title` | string | Yes | The title of the milestone. |
| `description` | string | Yes |  |
| `creator` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `open_issues` | integer | Yes |  |
| `closed_issues` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `closed_at` | string (date-time) | Yes |  |
| `due_on` | string (date-time) | Yes |  |

