# webhook-repository-renamed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: renamed | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository` | object | Yes |  |

#### `changes.repository`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | object | Yes |  |

