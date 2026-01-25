# organization-actions-variable

Organization variable for GitHub Actions.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the variable. |
| `value` | string | Yes | The value of the variable. |
| `created_at` | string (date-time) | Yes | The date and time at which the variable was created, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `updated_at` | string (date-time) | Yes | The date and time at which the variable was last updated, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `visibility` | enum: all, private, selected | Yes | Visibility of a variable |
| `selected_repositories_url` | string (uri) | No |  |

