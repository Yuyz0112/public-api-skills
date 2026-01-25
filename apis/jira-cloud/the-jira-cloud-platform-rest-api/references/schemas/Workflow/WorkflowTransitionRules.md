# WorkflowTransitionRules

A workflow with transition rules.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditions` | AppWorkflowTransitionRule[] | No | The list of conditions within the workflow. |
| `postFunctions` | AppWorkflowTransitionRule[] | No | The list of post functions within the workflow. |
| `validators` | AppWorkflowTransitionRule[] | No | The list of validators within the workflow. |
| `workflowId` | [WorkflowId](WorkflowId.md) | Yes |  |

