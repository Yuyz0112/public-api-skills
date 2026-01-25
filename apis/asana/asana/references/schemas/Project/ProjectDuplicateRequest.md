# ProjectDuplicateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the new project. |
| `team` | string | No | Sets the team of the new project. If team is not defined, the new project will be in the same team as the the original project. |
| `include` | string | No | A comma-separated list of elements to include when duplicating a project.
Some elements are automatically included and cannot be excluded,
while others are **optional** and must be explicitly specified in this field.

**Auto-included fields (non-configurable)**
- Tasks
- [Project Views](https://asana.com/features/project-management/project-views)
(i.e., tabs in a project such as List, Board, Dashboard, etc.)
- [Rules](https://help.asana.com/s/article/rules)

*Note: The Owner of the Rules copied to the new project is the user who performs the API call.
If the duplication is performed using a [Service Account](/docs/authentication#/service-account),
note that Service Accounts cannot access the UI to modify or pause Rules.
To prevent unwanted automation behavior, consider pausing Rules in the source project before duplication —
their active/paused state is preserved in the new project.*

**Optional fields (configurable)**
- allocations
- forms
- members
- notes
- permissions
- task_assignee
- task_attachments
- task_dates
- task_dependencies
- task_followers
- task_notes
- task_projects
- task_subtasks
- task_tags
- task_templates
- task_type_default |
| `schedule_dates` | object | No | A dictionary of options to auto-shift dates. `task_dates` must be included to use this option. Requires `should_skip_weekends` and either `start_on` or `due_on`, but not both. |

## Nested Fields

### `schedule_dates`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `should_skip_weekends` | boolean | No | **Required**: Determines if the auto-shifted dates should skip weekends. |
| `due_on` | string | No | Sets the last due date in the duplicated project to the given date. The rest of the due dates will be offset by the same amount as the due dates in the original project. |
| `start_on` | string | No | Sets the first start date in the duplicated project to the given date. The rest of the start dates will be offset by the same amount as the start dates in the original project. |

