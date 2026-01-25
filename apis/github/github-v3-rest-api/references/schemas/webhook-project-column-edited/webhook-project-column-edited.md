# webhook-project-column-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `project_column` | [webhooks_project_column](webhooks-project-column.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | object | No |  |

#### `changes.name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

