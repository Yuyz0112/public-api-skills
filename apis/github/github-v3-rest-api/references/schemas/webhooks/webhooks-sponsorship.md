# webhooks_sponsorship

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | Yes |  |
| `maintainer` | object | No |  |
| `node_id` | string | Yes |  |
| `privacy_level` | string | Yes |  |
| `sponsor` | object | Yes |  |
| `sponsorable` | object | Yes |  |
| `tier` | object | Yes | The `tier_changed` and `pending_tier_change` will include the original tier before the change or pending change. For more information, see the pending tier change payload. |

## Nested Fields

### `maintainer`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar_url` | string | No |  |
| `events_url` | string | No |  |
| `followers_url` | string | No |  |
| `following_url` | string | No |  |
| `gists_url` | string | No |  |
| `gravatar_id` | string | No |  |
| `html_url` | string | No |  |
| `id` | integer | No |  |
| `login` | string | No |  |
| `node_id` | string | No |  |
| `organizations_url` | string | No |  |
| `received_events_url` | string | No |  |
| `repos_url` | string | No |  |
| `site_admin` | boolean | No |  |
| `starred_url` | string | No |  |
| `subscriptions_url` | string | No |  |
| `type` | string | No |  |
| `url` | string | No |  |
| `user_view_type` | string | No |  |

### `sponsor`

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

### `sponsorable`

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

### `tier`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | Yes |  |
| `description` | string | Yes |  |
| `is_custom_ammount` | boolean | No |  |
| `is_custom_amount` | boolean | No |  |
| `is_one_time` | boolean | Yes |  |
| `monthly_price_in_cents` | integer | Yes |  |
| `monthly_price_in_dollars` | integer | Yes |  |
| `name` | string | Yes |  |
| `node_id` | string | Yes |  |

