# organization-programmatic-access-grant-request

Minimal representation of an organization programmatic access grant request for enumerations

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the request for access via fine-grained personal access token. The `pat_request_id` used to review PAT requests. |
| `reason` | string | Yes | Reason for requesting access. |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `repository_selection` | enum: none, all, subset | Yes | Type of repository selection requested. |
| `repositories_url` | string | Yes | URL to the list of repositories requested to be accessed via fine-grained personal access token. Should only be followed when `repository_selection` is `subset`. |
| `permissions` | object | Yes | Permissions requested, categorized by type of permission. |
| `created_at` | string | Yes | Date and time when the request for access was created. |
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

