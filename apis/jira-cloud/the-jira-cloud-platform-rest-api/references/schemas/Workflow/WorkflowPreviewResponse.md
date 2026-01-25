# WorkflowPreviewResponse

The preview workflow response containing workflows and statuses.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `statuses` | JiraWorkflowPreviewStatus[] | No | The list of statuses referenced by the workflows. |
| `workflows` | WorkflowPreview[] | No | The list of workflows. The workflows are returned in the same order as specified in the request. |

