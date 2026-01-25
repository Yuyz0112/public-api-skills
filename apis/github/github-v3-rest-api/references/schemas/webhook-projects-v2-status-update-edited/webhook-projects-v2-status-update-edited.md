# webhook-projects-v2-status-update-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | Yes |  |
| `projects_v2_status_update` | [projects-v2-status-update](projects-v2-status-update.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | object | No |  |
| `status` | object | No |  |
| `start_date` | object | No |  |
| `target_date` | object | No |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |
| `to` | string | No |  |

#### `changes.status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | enum: INACTIVE, ON_TRACK, AT_RISK... | No |  |
| `to` | enum: INACTIVE, ON_TRACK, AT_RISK... | No |  |

#### `changes.start_date`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string (date) | No |  |
| `to` | string (date) | No |  |

#### `changes.target_date`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string (date) | No |  |
| `to` | string (date) | No |  |

