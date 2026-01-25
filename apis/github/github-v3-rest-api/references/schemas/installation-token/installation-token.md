# installation-token

Authentication token for a GitHub App installed on a user or org.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `token` | string | Yes |  |
| `expires_at` | string | Yes |  |
| `permissions` | [app-permissions](app-permissions.md) | No |  |
| `repository_selection` | enum: all, selected | No |  |
| `repositories` | repository[] | No |  |
| `single_file` | string | No |  |
| `has_multiple_single_files` | boolean | No |  |
| `single_file_paths` | string[] | No |  |

