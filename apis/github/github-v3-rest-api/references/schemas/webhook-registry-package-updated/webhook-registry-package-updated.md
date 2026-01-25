# webhook-registry-package-updated

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: updated | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `registry_package` | object | Yes |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `registry_package`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | Yes |  |
| `description` | any | Yes |  |
| `ecosystem` | string | Yes |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes |  |
| `namespace` | string | Yes |  |
| `owner` | object | Yes |  |
| `package_type` | string | Yes |  |
| `package_version` | object | Yes |  |
| `registry` | object | Yes |  |
| `updated_at` | string | Yes |  |

#### `registry_package.owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string | Yes |  |
| `events_url` | string | Yes |  |
| `followers_url` | string | Yes |  |
| `following_url` | string | Yes |  |
| `gists_url` | string | Yes |  |
| `gravatar_id` | string | Yes |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `node_id` | string | Yes |  |
| `organizations_url` | string | Yes |  |
| `received_events_url` | string | Yes |  |
| `repos_url` | string | Yes |  |
| `site_admin` | boolean | Yes |  |
| `starred_url` | string | Yes |  |
| `subscriptions_url` | string | Yes |  |
| `type` | string | Yes |  |
| `url` | string | Yes |  |
| `user_view_type` | string | No |  |

#### `registry_package.package_version`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | Yes |  |
| `body` | string | Yes |  |
| `body_html` | string | Yes |  |
| `created_at` | string | Yes |  |
| `description` | string | Yes |  |
| `docker_metadata` | object[] | No |  |
| `draft` | boolean | No |  |
| `html_url` | string | Yes |  |
| `id` | integer | Yes |  |
| `installation_command` | string | Yes |  |
| `manifest` | string | No |  |
| `metadata` | object[] | Yes |  |
| `name` | string | Yes |  |
| `package_files` | object[] | Yes |  |
| `package_url` | string | Yes |  |
| `prerelease` | boolean | No |  |
| `release` | object | No |  |
| `rubygems_metadata` | webhook-rubygems-metadata[] | No |  |
| `summary` | string | Yes |  |
| `tag_name` | string | No |  |
| `target_commitish` | string | Yes |  |
| `target_oid` | string | Yes |  |
| `updated_at` | string | Yes |  |
| `version` | string | Yes |  |

