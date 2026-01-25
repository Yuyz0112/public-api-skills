# BudgetTotalRequest

Defines how the total portion of a budget is configured. The total represents a user-defined target value, not an aggregated one. This object specifies whether the total is displayed and the current value for the selected budget_type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No | Indicates whether the total value is active and should be displayed in the budget. This flag primarily affects UI presentation and the response payload. |
| `value` | number | No | The user-set value for the total budget. When `budget_type` is `time`, represents minutes. When `budget_type` is `cost`, represents the monetary amount in the domain's currency. This value is stored separately for each `budget_type`, so switching between types preserves each value. |

