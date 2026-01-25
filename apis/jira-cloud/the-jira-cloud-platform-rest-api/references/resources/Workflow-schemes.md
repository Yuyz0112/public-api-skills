# Workflow schemes

This resource represents workflow schemes. Use it to manage workflow schemes and the workflow scheme's workflows and issue types.

A workflow scheme maps issue types to workflows. A workflow scheme can be associated with one or more projects, which enables the projects to use the workflow-issue type mappings.

Active workflow schemes (workflow schemes that are used by projects) cannot be edited. When an active workflow scheme is edited, a draft copy of the scheme is created. The draft workflow scheme is then be edited and published (replacing the active scheme).

See [Configuring workflow schemes](https://confluence.atlassian.com/x/tohKLg) for more information.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/workflowscheme` | Get all workflow schemes | [View](../operations/getAllWorkflowSchemes.md) |
| POST | `/rest/api/3/workflowscheme` | Create workflow scheme | [View](../operations/createWorkflowScheme.md) |
| POST | `/rest/api/3/workflowscheme/project/switch` | Switch workflow scheme for project | [View](../operations/switchWorkflowSchemeForProject.md) |
| POST | `/rest/api/3/workflowscheme/read` | Bulk get workflow schemes | [View](../operations/readWorkflowSchemes.md) |
| POST | `/rest/api/3/workflowscheme/update` | Update workflow scheme | [View](../operations/updateSchemes.md) |
| POST | `/rest/api/3/workflowscheme/update/mappings` | Get required status mappings for workflow scheme update | [View](../operations/getRequiredWorkflowSchemeMappings.md) |
| GET | `/rest/api/3/workflowscheme/{id}` | Get workflow scheme | [View](../operations/getWorkflowScheme.md) |
| PUT | `/rest/api/3/workflowscheme/{id}` | Classic update workflow scheme | [View](../operations/updateWorkflowScheme.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}` | Delete workflow scheme | [View](../operations/deleteWorkflowScheme.md) |
| GET | `/rest/api/3/workflowscheme/{id}/default` | Get default workflow | [View](../operations/getDefaultWorkflow.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/default` | Update default workflow | [View](../operations/updateDefaultWorkflow.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/default` | Delete default workflow | [View](../operations/deleteDefaultWorkflow.md) |
| GET | `/rest/api/3/workflowscheme/{id}/issuetype/{issueType}` | Get workflow for issue type in workflow scheme | [View](../operations/getWorkflowSchemeIssueType.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/issuetype/{issueType}` | Set workflow for issue type in workflow scheme | [View](../operations/setWorkflowSchemeIssueType.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/issuetype/{issueType}` | Delete workflow for issue type in workflow scheme | [View](../operations/deleteWorkflowSchemeIssueType.md) |
| GET | `/rest/api/3/workflowscheme/{id}/workflow` | Get issue types for workflows in workflow scheme | [View](../operations/getWorkflow.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/workflow` | Set issue types for workflow in workflow scheme | [View](../operations/updateWorkflowMapping.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/workflow` | Delete issue types for workflow in workflow scheme | [View](../operations/deleteWorkflowMapping.md) |
| GET | `/rest/api/3/workflowscheme/{workflowSchemeId}/projectUsages` | Get projects which are using a given workflow scheme | [View](../operations/getProjectUsagesForWorkflowScheme.md) |
