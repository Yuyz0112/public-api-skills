# webhook-installation-repositories-added

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: added | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [installation](installation.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repositories_added` | [webhooks_repositories_added](webhooks-repositories-added.md) | Yes |  |
| `repositories_removed` | object[] | Yes | An array of repository objects, which were removed from the installation. |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `repository_selection` | [webhooks_repository_selection](webhooks-repository-selection.md) | Yes |  |
| `requester` | [webhooks_user](webhooks-user.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `repositories_removed`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `full_name` | string | No |  |
| `id` | integer | No | Unique identifier of the repository |
| `name` | string | No | The name of the repository. |
| `node_id` | string | No |  |
| `private` | boolean | No | Whether the repository is private or public. |

