# Transition

Details of a workflow transition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | The description of the transition. |
| `from` | string[] | Yes | The statuses the transition can start from. |
| `id` | string | Yes | The ID of the transition. |
| `name` | string | Yes | The name of the transition. |
| `properties` | object | No | The properties of the transition. |
| `rules` | [WorkflowRules](WorkflowRules.md) | No |  |
| `screen` | [TransitionScreenDetails](TransitionScreenDetails.md) | No |  |
| `to` | string | Yes | The status the transition goes to. |
| `type` | enum: global, initial, directed | Yes | The type of the transition. |

