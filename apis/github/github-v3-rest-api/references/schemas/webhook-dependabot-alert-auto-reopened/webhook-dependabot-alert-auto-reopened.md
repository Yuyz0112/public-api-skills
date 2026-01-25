# webhook-dependabot-alert-auto-reopened

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: auto_reopened | Yes |  |
| `alert` | [dependabot-alert](dependabot-alert.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

