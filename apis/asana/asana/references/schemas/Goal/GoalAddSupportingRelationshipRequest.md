# GoalAddSupportingRelationshipRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `supporting_resource` | string | Yes | The gid of the supporting resource to add to the parent goal. Must be the gid of a goal, project, task, or portfolio. |
| `insert_before` | string | No | An id of a subgoal of this parent goal. The new subgoal will be added before the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. Currently only supported when adding a subgoal. |
| `insert_after` | string | No | An id of a subgoal of this parent goal. The new subgoal will be added after the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. Currently only supported when adding a subgoal. |
| `contribution_weight` | number | No | Defines how much the supporting goal’s progress contributes to the parent goal’s overall progress. When used with automatically calculated [Goal Metrics](/reference/creategoalmetric) (such as `progress_source = subgoal_progress`), this value must be greater than 0 for the subgoal to count toward the parent goal’s progress.
Accepts a number between 0 and 1 (inclusive). Defaults to `0`. |

