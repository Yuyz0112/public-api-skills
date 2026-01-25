# IssueFieldOptionScopeBean

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `global` | any | No | Defines the behavior of the option within the global context. If this property is set, even if set to an empty object, then the option is available in all projects. |
| `projects` | integer[] | No | DEPRECATED |
| `projects2` | ProjectScopeBean[] | No | Defines the projects in which the option is available and the behavior of the option within each project. Specify one object per project. The behavior of the option in a project context overrides the behavior in the global context. |

