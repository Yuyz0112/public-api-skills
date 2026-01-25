# webhooks_alert

The security alert of the vulnerable dependency.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `affected_package_name` | string | Yes |  |
| `affected_range` | string | Yes |  |
| `created_at` | string | Yes |  |
| `dismiss_reason` | string | No |  |
| `dismissed_at` | string | No |  |
| `dismisser` | object | No |  |
| `external_identifier` | string | Yes |  |
| `external_reference` | string (uri) | Yes |  |
| `fix_reason` | string | No |  |
| `fixed_at` | string (date-time) | No |  |
| `fixed_in` | string | No |  |
| `ghsa_id` | string | Yes |  |
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `number` | integer | Yes |  |
| `severity` | string | Yes |  |
| `state` | enum: open | Yes |  |

## Nested Fields

### `dismisser`

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

