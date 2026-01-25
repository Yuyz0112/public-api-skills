# webhook-secret-scanning-alert-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes |  |
| `alert` | [secret-scanning-alert-webhook](secret-scanning-alert-webhook.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

