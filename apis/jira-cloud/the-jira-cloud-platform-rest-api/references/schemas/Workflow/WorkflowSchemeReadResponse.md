# WorkflowSchemeReadResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultWorkflow` | [WorkflowMetadataRestModel](WorkflowMetadataRestModel.md) | No |  |
| `description` | string | No | The description of the workflow scheme. |
| `id` | string | Yes | The ID of the workflow scheme. |
| `name` | string | Yes | The name of the workflow scheme. |
| `scope` | [WorkflowScope](WorkflowScope.md) | Yes |  |
| `taskId` | string | No | Indicates if there's an [asynchronous task](#async-operations) for this workflow scheme. |
| `version` | [DocumentVersion](DocumentVersion.md) | Yes |  |
| `workflowsForIssueTypes` | WorkflowMetadataAndIssueTypeRestModel[] | Yes | Mappings from workflows to issue types. |

