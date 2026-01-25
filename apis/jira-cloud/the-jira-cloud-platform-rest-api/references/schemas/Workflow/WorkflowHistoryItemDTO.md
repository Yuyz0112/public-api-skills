# WorkflowHistoryItemDTO

A single entry in the WorkflowHistoryPage.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `isIntermediate` | boolean | No | Whether the version is an intermediate workflow state, sometimes created during workflow updates. |
| `workflowId` | string | No |  |
| `workflowVersion` | integer (int64) | No |  |
| `writtenAt` | string | No | The timestamp when this workflow version was created. |

