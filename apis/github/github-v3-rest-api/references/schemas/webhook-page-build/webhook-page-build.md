# webhook-page-build

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `build` | object | Yes | The [List GitHub Pages builds](https://docs.github.com/rest/pages/pages#list-github-pages-builds) itself. |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `id` | integer | Yes |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `repository` | [repository-webhooks](repository-webhooks.md) | Yes |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `build`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `commit` | string | Yes |  |
| `created_at` | string | Yes |  |
| `duration` | integer | Yes |  |
| `error` | object | Yes |  |
| `pusher` | object | Yes |  |
| `status` | string | Yes |  |
| `updated_at` | string | Yes |  |
| `url` | string (uri) | Yes |  |

#### `build.error`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | Yes |  |

#### `build.pusher`

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

