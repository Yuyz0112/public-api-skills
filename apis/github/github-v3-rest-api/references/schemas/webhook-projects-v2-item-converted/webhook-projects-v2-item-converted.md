# webhook-projects-v2-item-converted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: converted | Yes |  |
| `changes` | object | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2_item` | [projects-v2-item](projects-v2-item.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `content_type` | object | No |  |

#### `changes.content_type`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

