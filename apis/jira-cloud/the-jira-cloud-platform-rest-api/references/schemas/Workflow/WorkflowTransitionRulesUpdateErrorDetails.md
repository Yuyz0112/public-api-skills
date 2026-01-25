# WorkflowTransitionRulesUpdateErrorDetails

Details of any errors encountered while updating workflow transition rules for a workflow.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ruleUpdateErrors` | object | Yes | A list of transition rule update errors, indexed by the transition rule ID. Any transition rule that appears here wasn't updated. |
| `updateErrors` | string[] | Yes | The list of errors that specify why the workflow update failed. The workflow was not updated if the list contains any entries. |
| `workflowId` | [WorkflowId](WorkflowId.md) | Yes |  |

