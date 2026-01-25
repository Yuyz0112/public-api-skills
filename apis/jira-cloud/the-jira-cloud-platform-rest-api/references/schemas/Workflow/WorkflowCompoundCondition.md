# WorkflowCompoundCondition

A compound workflow transition rule condition. This object returns `nodeType` as `compound`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conditions` | WorkflowCondition[] | Yes | The list of workflow conditions. |
| `nodeType` | string | Yes |  |
| `operator` | enum: AND, OR | Yes | The compound condition operator. |

