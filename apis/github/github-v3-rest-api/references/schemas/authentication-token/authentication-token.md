# authentication-token

Authentication Token

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `token` | string | Yes | The token used for authentication |
| `expires_at` | string (date-time) | Yes | The time this token expires |
| `permissions` | object | No |  |
| `repositories` | repository[] | No | The repositories this token has access to |
| `single_file` | string | No |  |
| `repository_selection` | enum: all, selected | No | Describe whether all repositories have been selected or there's a selection involved |

