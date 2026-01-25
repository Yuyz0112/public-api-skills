# organization-programmatic-access-grant

Minimal representation of an organization programmatic access grant for enumerations

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the fine-grained personal access token grant. The `pat_id` used to get details about an approved fine-grained personal access token. |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `repository_selection` | enum: none, all, subset | Yes | Type of repository selection requested. |
| `repositories_url` | string | Yes | URL to the list of repositories the fine-grained personal access token can access. Only follow when `repository_selection` is `subset`. |
| `permissions` | object | Yes | Permissions requested, categorized by type of permission. |
| `access_granted_at` | string | Yes | Date and time when the fine-grained personal access token was approved to access the organization. |
| `token_id` | integer | Yes | Unique identifier of the user's token. This field can also be found in audit log events and the organization's settings for their PAT grants. |
| `token_name` | string | Yes | The name given to the user's token. This field can also be found in an organization's settings page for Active Tokens. |
| `token_expired` | boolean | Yes | Whether the associated fine-grained personal access token has expired. |
| `token_expires_at` | string | Yes | Date and time when the associated fine-grained personal access token expires. |
| `token_last_used_at` | string | Yes | Date and time when the associated fine-grained personal access token was last used for authentication. |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization` | object | No |  |
| `repository` | object | No |  |
| `other` | object | No |  |

