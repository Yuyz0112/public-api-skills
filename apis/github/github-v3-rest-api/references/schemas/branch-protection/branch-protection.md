# branch-protection

Branch Protection

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string | No |  |
| `enabled` | boolean | No |  |
| `required_status_checks` | [protected-branch-required-status-check](protected-branch-required-status-check.md) | No |  |
| `enforce_admins` | [protected-branch-admin-enforced](protected-branch-admin-enforced.md) | No |  |
| `required_pull_request_reviews` | [protected-branch-pull-request-review](protected-branch-pull-request-review.md) | No |  |
| `restrictions` | [branch-restriction-policy](branch-restriction-policy.md) | No |  |
| `required_linear_history` | object | No |  |
| `allow_force_pushes` | object | No |  |
| `allow_deletions` | object | No |  |
| `block_creations` | object | No |  |
| `required_conversation_resolution` | object | No |  |
| `name` | string | No |  |
| `protection_url` | string | No |  |
| `required_signatures` | object | No |  |
| `lock_branch` | object | No | Whether to set the branch as read-only. If this is true, users will not be able to push to the branch. |
| `allow_fork_syncing` | object | No | Whether users can pull changes from upstream when the branch is locked. Set to `true` to allow fork syncing. Set to `false` to prevent fork syncing. |

## Nested Fields

### `required_linear_history`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `allow_force_pushes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `allow_deletions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `block_creations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `required_conversation_resolution`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `required_signatures`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `enabled` | boolean | Yes |  |

### `lock_branch`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `allow_fork_syncing`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

