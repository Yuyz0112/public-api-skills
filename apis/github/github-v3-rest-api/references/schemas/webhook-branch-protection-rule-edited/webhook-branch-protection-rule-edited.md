# webhook-branch-protection-rule-edited

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: edited | Yes |  |
| `changes` | object | No | If the action was `edited`, the changes to the rule. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `rule` | [webhooks_rule](webhooks-rule.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `admin_enforced` | object | No |  |
| `authorized_actor_names` | object | No |  |
| `authorized_actors_only` | object | No |  |
| `authorized_dismissal_actors_only` | object | No |  |
| `linear_history_requirement_enforcement_level` | object | No |  |
| `lock_branch_enforcement_level` | object | No |  |
| `lock_allows_fork_sync` | object | No |  |
| `pull_request_reviews_enforcement_level` | object | No |  |
| `require_last_push_approval` | object | No |  |
| `required_status_checks` | object | No |  |
| `required_status_checks_enforcement_level` | object | No |  |

#### `changes.admin_enforced`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | Yes |  |

#### `changes.authorized_actor_names`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string[] | Yes |  |

#### `changes.authorized_actors_only`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | Yes |  |

#### `changes.authorized_dismissal_actors_only`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | Yes |  |

#### `changes.linear_history_requirement_enforcement_level`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | enum: off, non_admins, everyone | Yes |  |

#### `changes.lock_branch_enforcement_level`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | enum: off, non_admins, everyone | Yes |  |

#### `changes.lock_allows_fork_sync`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | Yes |  |

#### `changes.pull_request_reviews_enforcement_level`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | enum: off, non_admins, everyone | Yes |  |

#### `changes.require_last_push_approval`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | boolean | Yes |  |

#### `changes.required_status_checks`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string[] | Yes |  |

#### `changes.required_status_checks_enforcement_level`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | enum: off, non_admins, everyone | Yes |  |

