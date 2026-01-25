# JiraWorkflowPreviewStatus

Details of a status.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the status. |
| `id` | string | No | The ID of the status. |
| `name` | string | No | The name of the status. |
| `rawName` | string | No | The raw name of the status. |
| `scope` | [WorkflowPreviewScope](WorkflowPreviewScope.md) | No |  |
| `statusCategory` | enum: TODO, IN_PROGRESS, DONE | No | The category of the status. |
| `statusReference` | string | No | The reference of the status. Unique within this response but not guaranteed to be stable across requests. |

