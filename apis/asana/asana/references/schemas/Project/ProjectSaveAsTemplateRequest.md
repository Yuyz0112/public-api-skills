# ProjectSaveAsTemplateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the new project template. |
| `team` | string | No | Sets the team of the new project template. If the project exists in an organization, specify team and not workspace. |
| `workspace` | string | No | Sets the workspace of the new project template. Only specify workspace if the project exists in a workspace. |
| `public` | boolean | Yes | Sets the project template to public to its team. |

