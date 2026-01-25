# webhook-sponsorship-created

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: created | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |
| `sponsorship` | [webhooks_sponsorship](webhooks-sponsorship.md) | Yes |  |

