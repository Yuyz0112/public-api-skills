# webhook-pull-request-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes | The changes to the comment if the action was `edited`. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `number` | [webhooks_number](webhooks-number.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `pull_request` | [pull-request-webhook](pull-request-webhook.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `base` | object | No |  |
| `body` | object | No |  |
| `title` | object | No |  |

#### `changes.base`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ref` | object | Yes |  |
| `sha` | object | Yes |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the body if the action was `edited`. |

#### `changes.title`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the title if the action was `edited`. |

