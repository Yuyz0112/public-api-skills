# WorkflowCreate

The details of the workflows to create.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | No | The description of the workflow to create. |
| `loopedTransitionContainerLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `name` | string | Yes | The name of the workflow to create. |
| `startPointLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `statuses` | StatusLayoutUpdate[] | Yes | The statuses associated with this workflow. |
| `transitions` | TransitionUpdateDTO[] | Yes | The transitions of this workflow. |

