# webhook-organization-member-removed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: member_removed | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `membership` | [webhooks_membership](webhooks-membership.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

