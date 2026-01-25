# webhook-discussion-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | No |  |
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
| `body` | object | No |  |
| `title` | object | No |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

#### `changes.title`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

