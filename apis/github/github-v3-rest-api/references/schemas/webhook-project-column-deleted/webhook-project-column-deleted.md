# webhook-project-column-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `project_column` | [webhooks_project_column](webhooks-project-column.md) | Yes |  |
| `repository` | [nullable-repository-webhooks](nullable-repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

