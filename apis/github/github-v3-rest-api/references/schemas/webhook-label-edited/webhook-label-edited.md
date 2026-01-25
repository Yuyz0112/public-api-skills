# webhook-label-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | No | The changes to the label if the action was `edited`. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `label` | [webhooks_label](webhooks-label.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `color` | object | No |  |
| `description` | object | No |  |
| `name` | object | No |  |

#### `changes.color`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the color if the action was `edited`. |

#### `changes.description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the description if the action was `edited`. |

#### `changes.name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the name if the action was `edited`. |

