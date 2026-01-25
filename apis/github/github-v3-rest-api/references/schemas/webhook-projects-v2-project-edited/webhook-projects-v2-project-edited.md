# webhook-projects-v2-project-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2` | [projects-v2](projects-v2.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | object | No |  |
| `public` | object | No |  |
| `short_description` | object | No |  |
| `title` | object | No |  |

#### `changes.description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

#### `changes.public`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | No |  |
| `to` | boolean | No |  |

#### `changes.short_description`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

#### `changes.title`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

