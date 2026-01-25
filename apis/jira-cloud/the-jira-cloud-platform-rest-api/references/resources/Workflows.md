# Workflows

This resource represents workflows. Use it to:

 *  Get workflows
 *  Create workflows
 *  Update workflows
 *  Delete inactive workflows
 *  Get workflow capabilities

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/workflow` | Get all workflows | [View](../operations/getAllWorkflows.md) |
| POST | `/rest/api/3/workflow` | Create workflow | [View](../operations/createWorkflow.md) |
| POST | `/rest/api/3/workflow/history` | Read workflow version from history | [View](../operations/readWorkflowFromHistory.md) |
| POST | `/rest/api/3/workflow/history/list` | List workflow history entries | [View](../operations/listWorkflowHistory.md) |
| GET | `/rest/api/3/workflow/search` | Get workflows paginated | [View](../operations/getWorkflowsPaginated.md) |
| DELETE | `/rest/api/3/workflow/{entityId}` | Delete inactive workflow | [View](../operations/deleteInactiveWorkflow.md) |
| GET | `/rest/api/3/workflow/{workflowId}/project/{projectId}/issueTypeUsages` | Get issue types in a project that are using a given workflow | [View](../operations/getWorkflowProjectIssueTypeUsages.md) |
| GET | `/rest/api/3/workflow/{workflowId}/projectUsages` | Get projects using a given workflow | [View](../operations/getProjectUsagesForWorkflow.md) |
| GET | `/rest/api/3/workflow/{workflowId}/workflowSchemes` | Get workflow schemes which are using a given workflow | [View](../operations/getWorkflowSchemeUsagesForWorkflow.md) |
| POST | `/rest/api/3/workflows` | Bulk get workflows | [View](../operations/readWorkflows.md) |
| GET | `/rest/api/3/workflows/capabilities` | Get available workflow capabilities | [View](../operations/workflowCapabilities.md) |
| POST | `/rest/api/3/workflows/create` | Bulk create workflows | [View](../operations/createWorkflows.md) |
| POST | `/rest/api/3/workflows/create/validation` | Validate create workflows | [View](../operations/validateCreateWorkflows.md) |
| GET | `/rest/api/3/workflows/defaultEditor` | Get the user's default workflow editor | [View](../operations/getDefaultEditor.md) |
| POST | `/rest/api/3/workflows/preview` | Preview workflow | [View](../operations/readWorkflowPreviews.md) |
| GET | `/rest/api/3/workflows/search` | Search workflows | [View](../operations/searchWorkflows.md) |
| POST | `/rest/api/3/workflows/update` | Bulk update workflows | [View](../operations/updateWorkflows.md) |
| POST | `/rest/api/3/workflows/update/validation` | Validate update workflows | [View](../operations/validateUpdateWorkflows.md) |
