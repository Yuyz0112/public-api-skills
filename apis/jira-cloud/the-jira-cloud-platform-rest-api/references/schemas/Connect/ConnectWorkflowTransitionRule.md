# ConnectWorkflowTransitionRule

A workflow transition rule.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `configuration` | [RuleConfiguration](RuleConfiguration.md) | Yes |  |
| `id` | string | Yes | The ID of the transition rule. |
| `key` | string | Yes | The key of the rule, as defined in the Connect app descriptor. |
| `transition` | [WorkflowTransition](WorkflowTransition.md) | No |  |

