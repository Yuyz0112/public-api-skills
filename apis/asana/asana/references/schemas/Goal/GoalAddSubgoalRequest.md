# GoalAddSubgoalRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subgoal` | string | Yes | The goal gid to add as subgoal to a parent goal |
| `insert_before` | string | No | An id of a subgoal of this parent goal. The new subgoal will be added before the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. |
| `insert_after` | string | No | An id of a subgoal of this parent goal. The new subgoal will be added after the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. |

