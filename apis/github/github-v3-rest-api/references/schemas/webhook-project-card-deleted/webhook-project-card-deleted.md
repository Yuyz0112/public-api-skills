# webhook-project-card-deleted

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `action` | enum: deleted | Yes |  |
| `enterprise` | [enterprise-webhooks](enterprise-webhooks.md) | No |  |
| `installation` | [simple-installation](simple-installation.md) | No |  |
| `organization` | [organization-simple-webhooks](organization-simple-webhooks.md) | No |  |
| `project_card` | object | Yes |  |
| `repository` | [nullable-repository-webhooks](nullable-repository-webhooks.md) | No |  |
| `sender` | [simple-user](simple-user.md) | Yes |  |

## Nested Fields

### `project_card`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `after_id` | integer | No |  |
| `archived` | boolean | Yes | Whether or not the card is archived |
| `column_id` | integer | Yes |  |
| `column_url` | string (uri) | Yes |  |
| `content_url` | string (uri) | No |  |
| `created_at` | string (date-time) | Yes |  |
| `creator` | object | Yes |  |
| `id` | integer | Yes | The project card's ID |
| `node_id` | string | Yes |  |
| `note` | string | Yes |  |
| `project_url` | string (uri) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `url` | string (uri) | Yes |  |

#### `project_card.creator`

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
| `type` | enum: Bot, User, Organization... | No |  |
| `url` | string (uri) | No |  |
| `user_view_type` | string | No |  |

