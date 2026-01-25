# personal-access-token-request

Details of a Personal Access Token Request.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the request for access via fine-grained personal access token. Used as the `pat_request_id` parameter in the list and review API calls. |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `permissions_added` | object | Yes | New requested permissions, categorized by type of permission. |
| `permissions_upgraded` | object | Yes | Requested permissions that elevate access for a previously approved request for access, categorized by type of permission. |
| `permissions_result` | object | Yes | Permissions requested, categorized by type of permission. This field incorporates `permissions_added` and `permissions_upgraded`. |
| `repository_selection` | enum: none, all, subset | Yes | Type of repository selection requested. |
| `repository_count` | integer | Yes | The number of repositories the token is requesting access to. This field is only populated when `repository_selection` is `subset`. |
| `repositories` | object[] | Yes | An array of repository objects the token is requesting access to. This field is only populated when `repository_selection` is `subset`. |
| `created_at` | string | Yes | Date and time when the request for access was created. |
| `token_id` | integer | Yes | Unique identifier of the user's token. This field can also be found in audit log events and the organization's settings for their PAT grants. |
| `token_name` | string | Yes | The name given to the user's token. This field can also be found in an organization's settings page for Active Tokens. |
| `token_expired` | boolean | Yes | Whether the associated fine-grained personal access token has expired. |
| `token_expires_at` | string | Yes | Date and time when the associated fine-grained personal access token expires. |
| `token_last_used_at` | string | Yes | Date and time when the associated fine-grained personal access token was last used for authentication. |

## Nested Fields

### `permissions_added`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization` | object | No |  |
| `repository` | object | No |  |
| `other` | object | No |  |

### `permissions_upgraded`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization` | object | No |  |
| `repository` | object | No |  |
| `other` | object | No |  |

### `permissions_result`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization` | object | No |  |
| `repository` | object | No |  |
| `other` | object | No |  |

### `repositories`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `full_name` | string | Yes |  |
| `id` | integer | Yes | Unique identifier of the repository |
| `name` | string | Yes | The name of the repository. |
| `node_id` | string | Yes |  |
| `private` | boolean | Yes | Whether the repository is private or public. |

