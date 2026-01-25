# webhook-discussion-category-changed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: category_changed | Yes |  |
| `changes` | object | Yes |  |
| `discussion` | [discussion](discussion.md) | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | object | Yes |  |

#### `changes.category`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | object | Yes |  |

