# WorkflowRulesSearchDetails

Details of workflow transition rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `invalidRules` | string[] | No | List of workflow rule IDs that do not belong to the workflow or can not be found. |
| `validRules` | WorkflowTransitionRules[] | No | List of valid workflow transition rules. |
| `workflowEntityId` | string (uuid) | No | The workflow ID. |

