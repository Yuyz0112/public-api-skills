# CreateWorkflowCondition

A workflow transition condition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditions` | CreateWorkflowCondition[] | No | The list of workflow conditions. |
| `configuration` | object | No | EXPERIMENTAL. The configuration of the transition rule. |
| `operator` | enum: AND, OR | No | The compound condition operator. |
| `type` | string | No | The type of the transition rule. |

