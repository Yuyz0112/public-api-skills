# WorkflowPreview

Details of a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the workflow. |
| `id` | string | No | The ID of the workflow. |
| `loopedTransitionContainerLayout` | [WorkflowPreviewLayout](WorkflowPreviewLayout.md) | No |  |
| `name` | string | No | The name of the workflow. |
| `queryContext` | ProjectIssueTypeQueryContext[] | No | The project and issue type context for this workflow query. |
| `scope` | [WorkflowPreviewScope](WorkflowPreviewScope.md) | No |  |
| `startPointLayout` | [WorkflowPreviewLayout](WorkflowPreviewLayout.md) | No |  |
| `statuses` | WorkflowPreviewStatus[] | No | The statuses referenced in this workflow. |
| `transitions` | TransitionPreview[] | No | The transitions of the workflow. |
| `version` | [WorkflowDocumentVersionBean](WorkflowDocumentVersionBean.md) | No |  |

