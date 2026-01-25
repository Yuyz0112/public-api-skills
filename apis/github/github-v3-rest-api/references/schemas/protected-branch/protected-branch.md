# protected-branch

Branch protections protect branches

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `required_status_checks` | [status-check-policy](status-check-policy.md) | No |  |
| `required_pull_request_reviews` | object | No |  |
| `required_signatures` | object | No |  |
| `enforce_admins` | object | No |  |
| `required_linear_history` | object | No |  |
| `allow_force_pushes` | object | No |  |
| `allow_deletions` | object | No |  |
| `restrictions` | [branch-restriction-policy](branch-restriction-policy.md) | No |  |
| `required_conversation_resolution` | object | No |  |
| `block_creations` | object | No |  |
| `lock_branch` | object | No | Whether to set the branch as read-only. If this is true, users will not be able to push to the branch. |
| `allow_fork_syncing` | object | No | Whether users can pull changes from upstream when the branch is locked. Set to `true` to allow fork syncing. Set to `false` to prevent fork syncing. |

## Nested Fields

### `required_pull_request_reviews`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `dismiss_stale_reviews` | boolean | No |  |
| `require_code_owner_reviews` | boolean | No |  |
| `required_approving_review_count` | integer | No |  |
| `require_last_push_approval` | boolean | No | Whether the most recent push must be approved by someone other than the person who pushed it. |
| `dismissal_restrictions` | object | No |  |
| `bypass_pull_request_allowances` | object | No |  |

#### `required_pull_request_reviews.dismissal_restrictions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `users_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `users` | simple-user[] | Yes |  |
| `teams` | team[] | Yes |  |
| `apps` | integration[] | No |  |

#### `required_pull_request_reviews.bypass_pull_request_allowances`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `users` | simple-user[] | Yes |  |
| `teams` | team[] | Yes |  |
| `apps` | integration[] | No |  |

### `required_signatures`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `enabled` | boolean | Yes |  |

### `enforce_admins`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `enabled` | boolean | Yes |  |

### `required_linear_history`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |

### `allow_force_pushes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |

### `allow_deletions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |

### `required_conversation_resolution`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `block_creations`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | Yes |  |

### `lock_branch`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

### `allow_fork_syncing`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `enabled` | boolean | No |  |

