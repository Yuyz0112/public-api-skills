# WorkflowTransitionLinks

The statuses the transition can start from, and the mapping of ports between the statuses.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fromPort` | integer (int32) | No | The port that the transition starts from. |
| `fromStatusReference` | string | No | The status that the transition starts from. |
| `toPort` | integer (int32) | No | The port that the transition goes to. |

