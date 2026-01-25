# WorkflowUpdate

The details of the workflows to update.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `defaultStatusMappings` | StatusMigration[] | No | The mapping of old to new status ID. |
| `description` | string | No | The new description for this workflow. |
| `id` | string | Yes | The ID of this workflow. |
| `loopedTransitionContainerLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `startPointLayout` | [WorkflowLayout](WorkflowLayout.md) | No |  |
| `statusMappings` | StatusMappingDTO[] | No | The mapping of old to new status ID for a specific project and issue type. |
| `statuses` | StatusLayoutUpdate[] | Yes | The statuses associated with this workflow. |
| `transitions` | TransitionUpdateDTO[] | Yes | The transitions of this workflow. |
| `version` | [DocumentVersion](DocumentVersion.md) | Yes |  |

