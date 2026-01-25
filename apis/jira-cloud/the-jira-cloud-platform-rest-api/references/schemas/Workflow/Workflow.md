# Workflow

Details about a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | string (date-time) | No | The creation date of the workflow. |
| `description` | string | Yes | The description of the workflow. |
| `hasDraftWorkflow` | boolean | No | Whether the workflow has a draft version. |
| `id` | [PublishedWorkflowId](PublishedWorkflowId.md) | Yes |  |
| `isDefault` | boolean | No | Whether this is the default workflow. |
| `operations` | [WorkflowOperations](WorkflowOperations.md) | No |  |
| `projects` | ProjectDetails[] | No | The projects the workflow is assigned to, through workflow schemes. |
| `schemes` | WorkflowSchemeIdName[] | No | The workflow schemes the workflow is assigned to. |
| `statuses` | WorkflowStatus[] | No | The statuses of the workflow. |
| `transitions` | Transition[] | No | The transitions of the workflow. |
| `updated` | string (date-time) | No | The last edited date of the workflow. |

