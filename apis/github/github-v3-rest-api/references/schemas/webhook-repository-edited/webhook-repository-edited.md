# webhook-repository-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
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
| `default_branch` | object | No |  |
| `description` | object | No |  |
| `homepage` | object | No |  |
| `topics` | object | No |  |

#### `changes.default_branch`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

#### `changes.description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

#### `changes.homepage`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

#### `changes.topics`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string[] | No |  |

