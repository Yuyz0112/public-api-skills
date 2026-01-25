# Goals

A goal is an object in the goal-tracking system that helps your organization drive measurable results.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/goals/{goal_gid}` | Get a goal | [View](../operations/getGoal.md) |
| PUT | `/goals/{goal_gid}` | Update a goal | [View](../operations/updateGoal.md) |
| DELETE | `/goals/{goal_gid}` | Delete a goal | [View](../operations/deleteGoal.md) |
| GET | `/goals` | Get goals | [View](../operations/getGoals.md) |
| POST | `/goals` | Create a goal | [View](../operations/createGoal.md) |
| POST | `/goals/{goal_gid}/setMetric` | Create a goal metric | [View](../operations/createGoalMetric.md) |
| POST | `/goals/{goal_gid}/setMetricCurrentValue` | Update a goal metric | [View](../operations/updateGoalMetric.md) |
| POST | `/goals/{goal_gid}/addFollowers` | Add a collaborator to a goal | [View](../operations/addFollowers.md) |
| POST | `/goals/{goal_gid}/removeFollowers` | Remove a collaborator from a goal | [View](../operations/removeFollowers.md) |
| GET | `/goals/{goal_gid}/parentGoals` | Get parent goals from a goal | [View](../operations/getParentGoalsForGoal.md) |
| POST | `/goals/{goal_gid}/addCustomFieldSetting` | Add a custom field to a goal | [View](../operations/addCustomFieldSettingForGoal.md) |
| POST | `/goals/{goal_gid}/removeCustomFieldSetting` | Remove a custom field from a goal | [View](../operations/removeCustomFieldSettingForGoal.md) |
