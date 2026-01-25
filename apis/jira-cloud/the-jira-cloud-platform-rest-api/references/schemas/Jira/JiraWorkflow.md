# JiraWorkflow

Details of a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string | No | The creation date of the workflow. |
| `description` | string | No | The description of the workflow. |
| `id` | string | No | The ID of the workflow. |
| `isEditable` | boolean | No | Indicates if the workflow can be edited. |
| `loopedTransitionContainerLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `name` | string | No | The name of the workflow. |
| `scope` | [WorkflowScope](WorkflowScope.md) | No |  |
| `startPointLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `statuses` | WorkflowReferenceStatus[] | No | The statuses referenced in this workflow. |
| `taskId` | string | No | If there is a current [asynchronous task](#async-operations) operation for this workflow. |
| `transitions` | WorkflowTransitions[] | No | The transitions of the workflow. |
| `updated` | string | No | The last edited date of the workflow. |
| `version` | [DocumentVersion](DocumentVersion.md) | No |  |

