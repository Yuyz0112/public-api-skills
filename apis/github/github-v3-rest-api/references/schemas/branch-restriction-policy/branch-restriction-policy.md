# branch-restriction-policy

Branch Restriction Policy

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `users_url` | string (uri) | Yes |  |
| `teams_url` | string (uri) | Yes |  |
| `apps_url` | string (uri) | Yes |  |
| `users` | object[] | Yes |  |
| `teams` | team[] | Yes |  |
| `apps` | object[] | Yes |  |

## Nested Fields

### `users`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | No |  |
| `id` | integer (int64) | No |  |
| `node_id` | string | No |  |
| `avatar_url` | string | No |  |
| `gravatar_id` | string | No |  |
| `url` | string | No |  |
| `html_url` | string | No |  |
| `followers_url` | string | No |  |
| `following_url` | string | No |  |
| `gists_url` | string | No |  |
| `starred_url` | string | No |  |
| `subscriptions_url` | string | No |  |
| `organizations_url` | string | No |  |
| `repos_url` | string | No |  |
| `events_url` | string | No |  |
| `received_events_url` | string | No |  |
| `type` | string | No |  |
| `site_admin` | boolean | No |  |
| `user_view_type` | string | No |  |

### `apps`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `slug` | string | No |  |
| `node_id` | string | No |  |
| `owner` | object | No |  |
| `name` | string | No |  |
| `client_id` | string | No |  |
| `description` | string | No |  |
| `external_url` | string | No |  |
| `html_url` | string | No |  |
| `created_at` | string | No |  |
| `updated_at` | string | No |  |
| `permissions` | object | No |  |
| `events` | string[] | No |  |

#### `apps.owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | No |  |
| `id` | integer | No |  |
| `node_id` | string | No |  |
| `url` | string | No |  |
| `repos_url` | string | No |  |
| `events_url` | string | No |  |
| `hooks_url` | string | No |  |
| `issues_url` | string | No |  |
| `members_url` | string | No |  |
| `public_members_url` | string | No |  |
| `avatar_url` | string | No |  |
| `description` | string | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string | No |  |
| `followers_url` | string | No |  |
| `following_url` | string | No |  |
| `gists_url` | string | No |  |
| `starred_url` | string | No |  |
| `subscriptions_url` | string | No |  |
| `organizations_url` | string | No |  |
| `received_events_url` | string | No |  |
| `type` | string | No |  |
| `site_admin` | boolean | No |  |
| `user_view_type` | string | No |  |

#### `apps.permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metadata` | string | No |  |
| `contents` | string | No |  |
| `issues` | string | No |  |
| `single_file` | string | No |  |

