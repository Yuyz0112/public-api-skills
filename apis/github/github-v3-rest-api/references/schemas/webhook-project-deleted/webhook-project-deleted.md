# webhook-project-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `project` | [webhooks_project](webhooks-project.md) | Yes |  |
| `repository` | [nullable-repository-webhooks](nullable-repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

