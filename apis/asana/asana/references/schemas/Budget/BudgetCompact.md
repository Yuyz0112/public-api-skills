# BudgetCompact

A *budget* object represents a budget for a given parent.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `budget_type` | enum: cost, time | No | The type of the budget, in "cost" or "time". The value of this property will dictate how the corresponding values for actual, estimate, and total are interpreted. |

