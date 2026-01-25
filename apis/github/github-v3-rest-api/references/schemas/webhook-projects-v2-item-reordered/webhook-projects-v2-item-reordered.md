# webhook-projects-v2-item-reordered

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: reordered | Yes |  |
| `changes` | object | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2_item` | [projects-v2-item](projects-v2-item.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `previous_projects_v2_item_node_id` | object | No |  |

#### `changes.previous_projects_v2_item_node_id`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

