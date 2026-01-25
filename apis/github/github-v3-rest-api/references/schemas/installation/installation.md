# installation

Installation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the installation. |
| `account` | any | Yes |  |
| `repository_selection` | enum: all, selected | Yes | Describe whether all repositories have been selected or there's a selection involved |
| `access_tokens_url` | string (uri) | Yes |  |
| `repositories_url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `app_id` | integer | Yes |  |
| `client_id` | string | No |  |
| `target_id` | integer | Yes | The ID of the user or organization this token is being scoped to. |
| `target_type` | string | Yes |  |
| `permissions` | [app-permissions](app-permissions.md) | Yes |  |
| `events` | string[] | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `single_file_name` | string | Yes |  |
| `has_multiple_single_files` | boolean | No |  |
| `single_file_paths` | string[] | No |  |
| `app_slug` | string | Yes |  |
| `suspended_by` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `suspended_at` | string (date-time) | Yes |  |
| `contact_email` | string | No |  |

