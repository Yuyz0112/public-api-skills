# IssueTypesWorkflowMapping

Details about the mapping between issue types and a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultMapping` | boolean | No | Whether the workflow is the default workflow for the workflow scheme. |
| `issueTypes` | string[] | No | The list of issue type IDs. |
| `updateDraftIfNeeded` | boolean | No | Whether a draft workflow scheme is created or updated when updating an active workflow scheme. The draft is updated with the new workflow-issue types mapping. Defaults to `false`. |
| `workflow` | string | No | The name of the workflow. Optional if updating the workflow-issue types mapping. |

