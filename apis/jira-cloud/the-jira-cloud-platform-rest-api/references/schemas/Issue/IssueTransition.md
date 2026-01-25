# IssueTransition

Details of an issue transition.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expand` | string | No | Expand options that include additional transition details in the response. |
| `fields` | object | No | Details of the fields associated with the issue transition screen. Use this information to populate `fields` and `update` in a transition request. |
| `hasScreen` | boolean | No | Whether there is a screen associated with the issue transition. |
| `id` | string | No | The ID of the issue transition. Required when specifying a transition to undertake. |
| `isAvailable` | boolean | No | Whether the transition is available to be performed. |
| `isConditional` | boolean | No | Whether the issue has to meet criteria before the issue transition is applied. |
| `isGlobal` | boolean | No | Whether the issue transition is global, that is, the transition is applied to issues regardless of their status. |
| `isInitial` | boolean | No | Whether this is the initial issue transition for the workflow. |
| `looped` | boolean | No |  |
| `name` | string | No | The name of the issue transition. |
| `to` | any | No | Details of the issue status after the transition. |

