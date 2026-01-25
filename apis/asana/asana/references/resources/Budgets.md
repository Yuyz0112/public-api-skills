# Budgets

A *budget* object represents a budget for a specific *parent* resource (such as a project).

Each budget tracks values either in *time* or *cost*, as determined by the *budget_type* field.

When *budget_type* is `time`, all values are expressed in minutes. When *budget_type* is `cost`, all values are expressed in the domain’s currency.

A budget can include up to three value objects: *estimate*, *actual*, and *total*. Each contains a `value`, `units`, and may include a `billable_status_filter` field.

**estimate** Represents the aggregated estimated effort on tasks attributed to the *parent*. For time budgets: total estimated minutes. For cost budgets: total estimated cost, computed as (estimated time × resource rate).

**actual** Represents the aggregated actual time logged on tasks attributed to the *parent*. For time budgets: total actual minutes from time tracking entries. For cost budgets: total actual cost, computed as (actual time × resource rate). The optional `billable_status_filter` limits aggregation to `billable`, `non_billable`, or `any` entries.

**total** A user-defined target value for the budget. Stored independently per budget type, so switching between *time* and *cost* preserves each type's value. For time budgets: stored and read as minutes. For cost budgets: stored and read in the domain's currency.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/budgets` | Get all budgets | [View](../operations/getBudgets.md) |
| POST | `/budgets` | Create a budget | [View](../operations/createBudget.md) |
| GET | `/budgets/{budget_gid}` | Get a budget | [View](../operations/getBudget.md) |
| PUT | `/budgets/{budget_gid}` | Update a budget | [View](../operations/updateBudget.md) |
| DELETE | `/budgets/{budget_gid}` | Delete a budget | [View](../operations/deleteBudget.md) |
