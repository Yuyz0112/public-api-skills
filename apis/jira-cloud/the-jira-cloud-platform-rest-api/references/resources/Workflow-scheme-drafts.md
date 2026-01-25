# Workflow scheme drafts

This resource represents draft workflow schemes. Use it to manage drafts of workflow schemes.

A workflow scheme maps issue types to workflows. A workflow scheme can be associated with one or more projects, which enables the projects to use the workflow-issue type mappings.

Active workflow schemes (workflow schemes that are used by projects) cannot be edited. Editing an active workflow scheme creates a draft copy of the scheme. The draft workflow scheme can then be edited and published (replacing the active scheme).

See [Configuring workflow schemes](https://confluence.atlassian.com/x/tohKLg) for more information.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/rest/api/3/workflowscheme/{id}/createdraft` | Create draft workflow scheme | [View](../operations/createWorkflowSchemeDraftFromParent.md) |
| GET | `/rest/api/3/workflowscheme/{id}/draft` | Get draft workflow scheme | [View](../operations/getWorkflowSchemeDraft.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/draft` | Update draft workflow scheme | [View](../operations/updateWorkflowSchemeDraft.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/draft` | Delete draft workflow scheme | [View](../operations/deleteWorkflowSchemeDraft.md) |
| GET | `/rest/api/3/workflowscheme/{id}/draft/default` | Get draft default workflow | [View](../operations/getDraftDefaultWorkflow.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/draft/default` | Update draft default workflow | [View](../operations/updateDraftDefaultWorkflow.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/draft/default` | Delete draft default workflow | [View](../operations/deleteDraftDefaultWorkflow.md) |
| GET | `/rest/api/3/workflowscheme/{id}/draft/issuetype/{issueType}` | Get workflow for issue type in draft workflow scheme | [View](../operations/getWorkflowSchemeDraftIssueType.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/draft/issuetype/{issueType}` | Set workflow for issue type in draft workflow scheme | [View](../operations/setWorkflowSchemeDraftIssueType.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/draft/issuetype/{issueType}` | Delete workflow for issue type in draft workflow scheme | [View](../operations/deleteWorkflowSchemeDraftIssueType.md) |
| POST | `/rest/api/3/workflowscheme/{id}/draft/publish` | Publish draft workflow scheme | [View](../operations/publishDraftWorkflowScheme.md) |
| GET | `/rest/api/3/workflowscheme/{id}/draft/workflow` | Get issue types for workflows in draft workflow scheme | [View](../operations/getDraftWorkflow.md) |
| PUT | `/rest/api/3/workflowscheme/{id}/draft/workflow` | Set issue types for workflow in workflow scheme | [View](../operations/updateDraftWorkflowMapping.md) |
| DELETE | `/rest/api/3/workflowscheme/{id}/draft/workflow` | Delete issue types for workflow in draft workflow scheme | [View](../operations/deleteDraftWorkflowMapping.md) |
