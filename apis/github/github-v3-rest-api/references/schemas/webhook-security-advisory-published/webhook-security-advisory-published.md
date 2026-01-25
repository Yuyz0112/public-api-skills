# webhook-security-advisory-published

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: published | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `security_advisory` | [webhooks_security_advisory](webhooks-security-advisory.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

