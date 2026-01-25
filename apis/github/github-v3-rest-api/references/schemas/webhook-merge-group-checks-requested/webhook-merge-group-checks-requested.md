# webhook-merge-group-checks-requested

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: checks_requested | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `merge_group` | [merge-group](merge-group.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

