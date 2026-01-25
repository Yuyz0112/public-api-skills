# webhooks_milestone_3

A collection of related issues and pull requests.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `closed_at` | string (date-time) | Yes |  |
| `closed_issues` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `creator` | object | Yes |  |
| `description` | string | Yes |  |
| `due_on` | string (date-time) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes |  |
| `labels_url` | string (uri) | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes | The number of the milestone. |
| `open_issues` | integer | Yes |  |
| `state` | enum: open, closed | Yes | The state of the milestone. |
| `title` | string | Yes | The title of the milestone. |
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

