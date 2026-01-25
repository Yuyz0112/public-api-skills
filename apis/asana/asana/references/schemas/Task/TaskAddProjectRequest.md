# TaskAddProjectRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `project` | string | Yes | The project to add the task to. |
| `insert_after` | string | No | A task in the project to insert the task after, or `null` to insert at the beginning of the list. When used with `section`, `null` will insert at the beginning of the specified section, otherwise the task must be in the specified section. |
| `insert_before` | string | No | A task in the project to insert the task before, or `null` to insert at the end of the list. When used with `section`, `null` will insert at the end of the specified section, otherwise the task must be in the specified section. |
| `section` | string | No | A section in the project to insert the task into. The task will be inserted at the bottom of the section unless combined with `insert_before: null` (end of section) or `insert_after: null` (beginning of section). Can also be combined with non-null `insert_before` or `insert_after` to position relative to a task within the section. |

