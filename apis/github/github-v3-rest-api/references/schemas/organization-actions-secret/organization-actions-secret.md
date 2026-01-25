# organization-actions-secret

Secrets for GitHub Actions for an organization.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the secret. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `visibility` | enum: all, private, selected | Yes | Visibility of a secret |
| `selected_repositories_url` | string (uri) | No |  |

