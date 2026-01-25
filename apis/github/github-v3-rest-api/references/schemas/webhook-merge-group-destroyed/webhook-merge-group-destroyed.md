# webhook-merge-group-destroyed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: destroyed | Yes |  |
| `reason` | enum: merged, invalidated, dequeued | No | Explains why the merge group is being destroyed. The group could have been merged, removed from the queue (dequeued), or invalidated by an earlier queue entry being dequeued (invalidated). |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `merge_group` | [merge-group](merge-group.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

