# WorkflowSchemeUpdateRequiredMappingsRequest

The request payload to get the required mappings for updating a workflow scheme.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultWorkflowId` | string | No | The ID of the new default workflow for this workflow scheme. Only used in global-scoped workflow schemes. If it isn't specified, is set to *Jira Workflow (jira)*. |
| `id` | string | Yes | The ID of the workflow scheme. |
| `workflowsForIssueTypes` | WorkflowSchemeAssociation[] | Yes | The new workflow to issue type mappings for this workflow scheme. |

