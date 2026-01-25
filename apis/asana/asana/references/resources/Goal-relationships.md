# Goal relationships

A goal relationship is an object representing the relationship between a goal and another goal, a project, a task, or a portfolio.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/goal_relationships/{goal_relationship_gid}` | Get a goal relationship | [View](../operations/getGoalRelationship.md) |
| PUT | `/goal_relationships/{goal_relationship_gid}` | Update a goal relationship | [View](../operations/updateGoalRelationship.md) |
| GET | `/goal_relationships` | Get goal relationships | [View](../operations/getGoalRelationships.md) |
| POST | `/goals/{goal_gid}/addSupportingRelationship` | Add a supporting goal relationship | [View](../operations/addSupportingRelationship.md) |
| POST | `/goals/{goal_gid}/removeSupportingRelationship` | Removes a supporting goal relationship | [View](../operations/removeSupportingRelationship.md) |
