# webhook-milestone-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes | The changes to the milestone if the action was `edited`. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `milestone` | [webhooks_milestone](webhooks-milestone.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | object | No |  |
| `due_on` | object | No |  |
| `title` | object | No |  |

#### `changes.description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the description if the action was `edited`. |

#### `changes.due_on`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the due date if the action was `edited`. |

#### `changes.title`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the title if the action was `edited`. |

