# TransitionUpdateDTO

The transition update data.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `actions` | WorkflowRuleConfiguration[] | No | The post-functions of the transition. |
| `conditions` | [ConditionGroupUpdate](ConditionGroupUpdate.md) | No |  |
| `customIssueEventId` | string | No | The custom event ID of the transition. |
| `description` | string | No | The description of the transition. |
| `id` | string | No | The ID of the transition. |
| `links` | WorkflowTransitionLinks[] | No | The statuses the transition can start from, and the mapping of ports between the statuses. |
| `name` | string | No | The name of the transition. |
| `properties` | object | No | The properties of the transition. |
| `toStatusReference` | string | No | The status the transition goes to. |
| `transitionScreen` | [WorkflowRuleConfiguration](WorkflowRuleConfiguration.md) | No |  |
| `triggers` | WorkflowTrigger[] | No | The triggers of the transition. |
| `type` | enum: INITIAL, GLOBAL, DIRECTED | No | The transition type. |
| `validators` | WorkflowRuleConfiguration[] | No | The validators of the transition. |

