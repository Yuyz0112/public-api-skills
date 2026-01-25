# MappingsByWorkflow

The status mappings by workflows. Status mappings are required when the new workflow for an issue type doesn't contain all statuses that the old workflow has. Status mappings can be provided by a combination of `statusMappingsByWorkflows` and `statusMappingsByIssueTypeOverride`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `newWorkflowId` | string | Yes | The ID of the new workflow. |
| `oldWorkflowId` | string | Yes | The ID of the old workflow. |
| `statusMappings` | WorkflowAssociationStatusMapping[] | Yes | The list of status mappings. |

