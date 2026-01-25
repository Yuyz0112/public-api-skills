# webhook-project-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | No | The changes to the project if the action was `edited`. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `project` | [webhooks_project](webhooks-project.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | object | No |  |
| `name` | object | No |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the body if the action was `edited`. |

#### `changes.name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The changes to the project if the action was `edited`. |

