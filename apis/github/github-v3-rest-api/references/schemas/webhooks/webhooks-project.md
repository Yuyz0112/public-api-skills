# webhooks_project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `body` | string | Yes | Body of the project |
| `columns_url` | string (uri) | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `creator` | object | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `name` | string | Yes | Name of the project |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `owner_url` | string (uri) | Yes |  |
| `state` | enum: open, closed | Yes | State of the project; either 'open' or 'closed' |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |

## Nested Fields

### `creator`

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

