# activity

Activity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `before` | string | Yes | The SHA of the commit before the activity. |
| `after` | string | Yes | The SHA of the commit after the activity. |
| `ref` | string | Yes | The full Git reference, formatted as `refs/heads/<branch name>`. |
| `timestamp` | string (date-time) | Yes | The time when the activity occurred. |
| `activity_type` | enum: push, force_push, branch_deletion... | Yes | The type of the activity that was performed. |
| `actor` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |

