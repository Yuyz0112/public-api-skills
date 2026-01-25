# TaskProgressBeanJsonNode

Details about a task.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the task. |
| `elapsedRuntime` | integer (int64) | Yes | The execution time of the task, in milliseconds. |
| `finished` | integer (int64) | No | A timestamp recording when the task was finished. |
| `id` | string | Yes | The ID of the task. |
| `lastUpdate` | integer (int64) | Yes | A timestamp recording when the task progress was last updated. |
| `message` | string | No | Information about the progress of the task. |
| `progress` | integer (int64) | Yes | The progress of the task, as a percentage complete. |
| `result` | any | No | The result of the task execution. |
| `self` | string (uri) | Yes | The URL of the task. |
| `started` | integer (int64) | No | A timestamp recording when the task was started. |
| `status` | enum: ENQUEUED, RUNNING, COMPLETE... | Yes | The status of the task. |
| `submitted` | integer (int64) | Yes | A timestamp recording when the task was submitted. |
| `submittedBy` | integer (int64) | Yes | The ID of the user who submitted the task. |

