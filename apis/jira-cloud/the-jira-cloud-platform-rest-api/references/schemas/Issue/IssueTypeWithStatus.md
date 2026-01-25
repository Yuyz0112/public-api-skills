# IssueTypeWithStatus

Status details for an issue type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The ID of the issue type. |
| `name` | string | Yes | The name of the issue type. |
| `self` | string | Yes | The URL of the issue type's status details. |
| `statuses` | StatusDetails[] | Yes | List of status details for the issue type. |
| `subtask` | boolean | Yes | Whether this issue type represents subtasks. |

