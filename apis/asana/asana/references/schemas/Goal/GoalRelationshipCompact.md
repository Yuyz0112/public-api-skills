# GoalRelationshipCompact

A *goal relationship* is an object representing the relationship between a goal and another goal, a project, a task, or a portfolio.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `gid` | string | No | Globally unique identifier of the resource, as a string. |
| `resource_type` | string | No | The base type of this resource. |
| `resource_subtype` | enum: subgoal, supporting_work | No | The subtype of this resource. Different subtypes retain many of the same fields and behavior, but may render differently in Asana or represent resources with different semantic meaning. |
| `supporting_resource` | any | No |  |
| `contribution_weight` | number | No | The weight that the supporting resource's progress contributes to the supported goal's progress. This can be 0, 1, or any value in between. |

