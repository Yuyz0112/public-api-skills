# TaskSetParentRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `parent` | string | Yes | The new parent of the task, or `null` for no parent. |
| `insert_after` | string | No | A subtask of the parent to insert the task after, or `null` to insert at the beginning of the list. |
| `insert_before` | string | No | A subtask of the parent to insert the task before, or `null` to insert at the end of the list. |

