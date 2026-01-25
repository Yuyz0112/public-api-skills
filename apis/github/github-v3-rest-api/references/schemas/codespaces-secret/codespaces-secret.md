# codespaces-secret

Secrets for a GitHub Codespace.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the secret |
| `created_at` | string (date-time) | Yes | The date and time at which the secret was created, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `updated_at` | string (date-time) | Yes | The date and time at which the secret was last updated, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `visibility` | enum: all, private, selected | Yes | The type of repositories in the organization that the secret is visible to |
| `selected_repositories_url` | string (uri) | Yes | The API URL at which the list of repositories this secret is visible to can be retrieved |

