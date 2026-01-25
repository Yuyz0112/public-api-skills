# IssueTypeWorkflowMapping

Details about the mapping between an issue type and a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `issueType` | string | No | The ID of the issue type. Not required if updating the issue type-workflow mapping. |
| `updateDraftIfNeeded` | boolean | No | Set to true to create or update the draft of a workflow scheme and update the mapping in the draft, when the workflow scheme cannot be edited. Defaults to `false`. Only applicable when updating the workflow-issue types mapping. |
| `workflow` | string | No | The name of the workflow. |

