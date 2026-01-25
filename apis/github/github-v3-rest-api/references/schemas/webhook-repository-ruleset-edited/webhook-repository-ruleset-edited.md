# webhook-repository-ruleset-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `repository_ruleset` | [repository-ruleset](repository-ruleset.md) | Yes |  |
| `changes` | object | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | object | No |  |
| `enforcement` | object | No |  |
| `conditions` | object | No |  |
| `rules` | object | No |  |

#### `changes.name`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |

#### `changes.enforcement`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | No |  |

#### `changes.conditions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added` | repository-ruleset-conditions[] | No |  |
| `deleted` | repository-ruleset-conditions[] | No |  |
| `updated` | object[] | No |  |

#### `changes.rules`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `added` | repository-rule[] | No |  |
| `deleted` | repository-rule[] | No |  |
| `updated` | object[] | No |  |

