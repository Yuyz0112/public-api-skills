# webhook-installation-target-renamed

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account` | object | Yes |  |
| `action` | enum: renamed | Yes |  |
| `changes` | object | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | Yes |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | No |  |
| `target_type` | string | Yes |  |

## Nested Fields

### `account`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `archived_at` | string | No |  |
| `avatar_url` | string | Yes |  |
| `created_at` | string | No |  |
| `description` | any | No |  |
| `events_url` | string | No |  |
| `followers` | integer | No |  |
| `followers_url` | string | No |  |
| `following` | integer | No |  |
| `following_url` | string | No |  |
| `gists_url` | string | No |  |
| `gravatar_id` | string | No |  |
| `has_organization_projects` | boolean | No |  |
| `has_repository_projects` | boolean | No |  |
| `hooks_url` | string | No |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `is_verified` | boolean | No |  |
| `issues_url` | string | No |  |
| `login` | string | No |  |
| `members_url` | string | No |  |
| `name` | string | No |  |
| `node_id` | string | Yes |  |
| `organizations_url` | string | No |  |
| `public_gists` | integer | No |  |
| `public_members_url` | string | No |  |
| `public_repos` | integer | No |  |
| `received_events_url` | string | No |  |
| `repos_url` | string | No |  |
| `site_admin` | boolean | No |  |
| `slug` | string | No |  |
| `starred_url` | string | No |  |
| `subscriptions_url` | string | No |  |
| `type` | string | No |  |
| `updated_at` | string | No |  |
| `url` | string | No |  |
| `website_url` | any | No |  |
| `user_view_type` | string | No |  |

### `changes`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | object | No |  |
| `slug` | object | No |  |

#### `changes.login`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

#### `changes.slug`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `from` | string | Yes |  |

