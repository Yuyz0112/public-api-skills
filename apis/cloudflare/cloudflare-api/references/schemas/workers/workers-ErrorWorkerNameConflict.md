# workers_ErrorWorkerNameConflict

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | enum: 10040 | Yes | Code indicating that a Worker with this name already exists. |
| `message` | string | Yes | Message explaining that the Worker name is already in use and suggesting to choose a different name. |

