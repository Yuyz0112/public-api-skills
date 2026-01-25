# WorkflowCreateRequest

The create workflows payload.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `scope` | [WorkflowScope](WorkflowScope.md) | No |  |
| `statuses` | WorkflowStatusUpdate[] | No | The statuses to associate with the workflows. |
| `workflows` | WorkflowCreate[] | No | The details of the workflows to create. |

