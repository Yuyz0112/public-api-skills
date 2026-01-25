# BudgetActualRequest

Defines the configuration of the actual portion of a budget. The actual value represents aggregated time tracking data attributed to the budget’s parent. This object controls which time entries are included based on their billable status. When no entries match the selected filter, the value will be 0.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billable_status_filter` | enum: billable, non_billable, any | No | Billable status filter applied to time tracking entries contributing to the actual value. Determines which entries are included in aggregation. When not provided, defaults to `billable`. |

