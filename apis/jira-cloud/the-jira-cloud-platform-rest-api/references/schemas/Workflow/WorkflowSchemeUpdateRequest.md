# WorkflowSchemeUpdateRequest

The update workflow scheme payload.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultWorkflowId` | string | No | The ID of the workflow for issue types without having a mapping defined in this workflow scheme. Only used in global-scoped workflow schemes. If the `defaultWorkflowId` isn't specified, this is set to *Jira Workflow (jira)*. |
| `description` | string | Yes | The new description for this workflow scheme. |
| `id` | string | Yes | The ID of this workflow scheme. |
| `name` | string | Yes | The new name for this workflow scheme. |
| `statusMappingsByIssueTypeOverride` | MappingsByIssueTypeOverride[] | No | Overrides, for the selected issue types, any status mappings provided in `statusMappingsByWorkflows`. Status mappings are required when the new workflow for an issue type doesn't contain all statuses that the old workflow has. Status mappings can be provided by a combination of `statusMappingsByWorkflows` and `statusMappingsByIssueTypeOverride`. |
| `statusMappingsByWorkflows` | MappingsByWorkflow[] | No | The status mappings by workflows. Status mappings are required when the new workflow for an issue type doesn't contain all statuses that the old workflow has. Status mappings can be provided by a combination of `statusMappingsByWorkflows` and `statusMappingsByIssueTypeOverride`. |
| `version` | [DocumentVersion](DocumentVersion.md) | Yes |  |
| `workflowsForIssueTypes` | WorkflowSchemeAssociation[] | No | Mappings from workflows to issue types. |

