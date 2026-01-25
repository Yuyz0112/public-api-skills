# CreateWorkflowTransitionDetails

The details of a workflow transition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the transition. The maximum length is 1000 characters. |
| `from` | string[] | No | The statuses the transition can start from. |
| `name` | string | Yes | The name of the transition. The maximum length is 60 characters. |
| `properties` | object | No | The properties of the transition. |
| `rules` | any | No | The rules of the transition. |
| `screen` | any | No | The screen of the transition. |
| `to` | string | Yes | The status the transition goes to. |
| `type` | enum: global, initial, directed | Yes | The type of the transition. |

