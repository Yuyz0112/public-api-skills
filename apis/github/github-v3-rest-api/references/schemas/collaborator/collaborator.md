# collaborator

Collaborator

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | Yes |  |
| `id` | integer (int64) | Yes |  |
| `email` | string | No |  |
| `name` | string | No |  |
| `node_id` | string | Yes |  |
| `avatar_url` | string (uri) | Yes |  |
| `gravatar_id` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `followers_url` | string (uri) | Yes |  |
| `following_url` | string | Yes |  |
| `gists_url` | string | Yes |  |
| `starred_url` | string | Yes |  |
| `subscriptions_url` | string (uri) | Yes |  |
| `organizations_url` | string (uri) | Yes |  |
| `repos_url` | string (uri) | Yes |  |
| `events_url` | string | Yes |  |
| `received_events_url` | string (uri) | Yes |  |
| `type` | string | Yes |  |
| `site_admin` | boolean | Yes |  |
| `permissions` | object | No |  |
| `role_name` | string | Yes |  |
| `user_view_type` | string | No |  |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pull` | boolean | Yes |  |
| `triage` | boolean | No |  |
| `push` | boolean | Yes |  |
| `maintain` | boolean | No |  |
| `admin` | boolean | Yes |  |

