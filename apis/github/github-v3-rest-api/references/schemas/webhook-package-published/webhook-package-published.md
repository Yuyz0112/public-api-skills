# webhook-package-published

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: published | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `package` | object | Yes | Information about the package. |
| `repository` | [repository-webhooks](repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `package`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | Yes |  |
| `description` | string | Yes |  |
| `ecosystem` | string | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes |  |
| `namespace` | string | Yes |  |
| `owner` | object | Yes |  |
| `package_type` | string | Yes |  |
| `package_version` | object | Yes |  |
| `registry` | object | Yes |  |
| `updated_at` | string | Yes |  |

#### `package.owner`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string (uri) | No |  |
| `deleted` | boolean | No |  |
| `email` | string | No |  |
| `events_url` | string (uri-template) | No |  |
| `followers_url` | string (uri) | No |  |
| `following_url` | string (uri-template) | No |  |
| `gists_url` | string (uri-template) | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes |  |
| `login` | string | Yes |  |
| `name` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string (uri) | No |  |
| `received_events_url` | string (uri) | No |  |
| `repos_url` | string (uri) | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string (uri-template) | No |  |
| `subscriptions_url` | string (uri) | No |  |
| `type` | enum: Bot, User, Organization | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

#### `package.package_version`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `author` | object | No |  |
| `body` | any | No |  |
| `body_html` | string | No |  |
| `container_metadata` | object | No |  |
| `created_at` | string | No |  |
| `description` | string | Yes |  |
| `docker_metadata` | object[] | No |  |
| `draft` | boolean | No |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `installation_command` | string | Yes |  |
| `manifest` | string | No |  |
| `metadata` | object[] | Yes |  |
| `name` | string | Yes |  |
| `npm_metadata` | object | No |  |
| `nuget_metadata` | object[] | No |  |
| `package_files` | object[] | Yes |  |
| `package_url` | string | No |  |
| `prerelease` | boolean | No |  |
| `release` | object | No |  |
| `rubygems_metadata` | webhook-rubygems-metadata[] | No |  |
| `source_url` | string | No |  |
| `summary` | string | Yes |  |
| `tag_name` | string | No |  |
| `target_commitish` | string | No |  |
| `target_oid` | string | No |  |
| `updated_at` | string | No |  |
| `version` | string | Yes |  |

#### `package.registry`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `about_url` | string (uri) | Yes |  |
| `name` | string | Yes |  |
| `type` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `vendor` | string | Yes |  |

