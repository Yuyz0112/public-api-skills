# private-user

Private User

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `login` | string | Yes |  |
| `id` | integer (int64) | Yes |  |
| `user_view_type` | string | No |  |
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
| `name` | string | Yes |  |
| `company` | string | Yes |  |
| `blog` | string | Yes |  |
| `location` | string | Yes |  |
| `email` | string (email) | Yes |  |
| `notification_email` | string (email) | No |  |
| `hireable` | boolean | Yes |  |
| `bio` | string | Yes |  |
| `twitter_username` | string | No |  |
| `public_repos` | integer | Yes |  |
| `public_gists` | integer | Yes |  |
| `followers` | integer | Yes |  |
| `following` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `private_gists` | integer | Yes |  |
| `total_private_repos` | integer | Yes |  |
| `owned_private_repos` | integer | Yes |  |
| `disk_usage` | integer | Yes |  |
| `collaborators` | integer | Yes |  |
| `two_factor_authentication` | boolean | Yes |  |
| `plan` | object | No |  |
| `business_plus` | boolean | No |  |
| `ldap_dn` | string | No |  |

## Nested Fields

### `plan`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `collaborators` | integer | Yes |  |
| `name` | string | Yes |  |
| `space` | integer | Yes |  |
| `private_repos` | integer | Yes |  |

