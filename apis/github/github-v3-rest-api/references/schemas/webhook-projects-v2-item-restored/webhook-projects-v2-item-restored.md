# webhook-projects-v2-item-restored

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: restored | Yes |  |
| `changes` | [webhooks_project_changes](webhooks-project-changes.md) | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2_item` | [projects-v2-item](projects-v2-item.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

