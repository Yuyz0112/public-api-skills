# webhook-installation-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [installation](installation.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repositories` | [webhooks_repositories](webhooks-repositories.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `requester` | any | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

