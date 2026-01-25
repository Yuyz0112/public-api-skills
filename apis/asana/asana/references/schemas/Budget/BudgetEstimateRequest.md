# BudgetEstimateRequest

Defines how the estimate portion of a budget is configured. This object controls whether the estimate is enabled, what data source it uses, and which tasks (by billable status) are included in calculating the estimate value. When disabled (enabled: false and source: none), the estimate is hidden and the API response will return `value: null` and `units: null` for this field.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `billable_status_filter` | enum: billable, non_billable, any | No | Billable status filter applied to the estimate when `source` is `tasks`. Ignored when `source` is `capacity_plans` or `none`. When not provided, defaults to `billable`. |
| `source` | enum: none, tasks, capacity_plans | No | The data source for the estimate. `tasks`: use task-level estimated time attributed to the parent. `capacity_plans`: use capacity plan estimates attributed to the parent. `none`: disables the estimate; only valid when `enabled` is `false`. When `enabled` is `true`, `source` must not be `none`. |
| `enabled` | boolean | No | Controls whether the estimate is displayed in the budget. This flag primarily affects UI presentation and the response payload. When `false` (and `source` is `none`), the estimate is hidden and the API response will return `value: null` and `units: null` for this field. |

