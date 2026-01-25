# projects-v2-draft-issue

A draft issue in a project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | number | Yes | The ID of the draft issue |
| `node_id` | string | Yes | The node ID of the draft issue |
| `title` | string | Yes | The title of the draft issue |
| `body` | string | No | The body content of the draft issue |
| `user` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `created_at` | string (date-time) | Yes | The time the draft issue was created |
| `updated_at` | string (date-time) | Yes | The time the draft issue was last updated |

