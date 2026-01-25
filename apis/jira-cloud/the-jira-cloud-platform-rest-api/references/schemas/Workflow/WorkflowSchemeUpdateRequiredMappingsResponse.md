# WorkflowSchemeUpdateRequiredMappingsResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `statusMappingsByIssueTypes` | RequiredMappingByIssueType[] | No | The list of required status mappings by issue type. |
| `statusMappingsByWorkflows` | RequiredMappingByWorkflows[] | No | The list of required status mappings by workflow. |
| `statuses` | StatusMetadata[] | No | The details of the statuses in the associated workflows. |
| `statusesPerWorkflow` | StatusesPerWorkflow[] | No | The statuses associated with each workflow. |

