# WorkflowUpdateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `statuses` | JiraWorkflowStatus[] | No | List of updated statuses. |
| `taskId` | string | No | If there is a [asynchronous task](#async-operations) operation, as a result of this update. |
| `workflows` | JiraWorkflow[] | No | List of updated workflows. |

