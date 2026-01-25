# webhook-secret-scanning-alert-location-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | No |  |
| `alert` | [secret-scanning-alert-webhook](secret-scanning-alert-webhook.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `location` | [secret-scanning-location](secret-scanning-location.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

