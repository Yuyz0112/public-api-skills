# webhook-projects-v2-item-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2_item` | [projects-v2-item](projects-v2-item.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

