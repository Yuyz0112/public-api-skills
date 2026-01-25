# webhook-release-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `release` | [webhooks_release](webhooks-release.md) | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | No |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | object | No |  |
| `name` | object | No |  |
| `tag_name` | object | No |  |
| `make_latest` | object | No |  |

#### `changes.body`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the body if the action was `edited`. |

#### `changes.name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the name if the action was `edited`. |

#### `changes.tag_name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes | The previous version of the tag_name if the action was `edited`. |

#### `changes.make_latest`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `to` | boolean | Yes | Whether this release was explicitly `edited` to be the latest. |

