# nullable-scoped-installation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `permissions` | [app-permissions](app-permissions.md) | Yes |  |
| `repository_selection` | enum: all, selected | Yes | Describe whether all repositories have been selected or there's a selection involved |
| `single_file_name` | string | Yes |  |
| `has_multiple_single_files` | boolean | No |  |
| `single_file_paths` | string[] | No |  |
| `repositories_url` | string (uri) | Yes |  |
| `account` | [simple-user](simple-user.md) | Yes |  |

