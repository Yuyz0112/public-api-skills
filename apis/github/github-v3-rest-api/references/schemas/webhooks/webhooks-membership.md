# webhooks_membership

The membership between the user and the organization. Not present when the action is `member_invited`.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `organization_url` | string (uri) | Yes |  |
| `role` | string | Yes |  |
| `direct_membership` | boolean | No | Whether the user has direct membership in the organization. |
| `enterprise_teams_providing_indirect_membership` | string[] | No | The slugs of the enterprise teams providing the user with indirect membership in the organization.
A limit of 100 enterprise team slugs is returned. |
| `state` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `user` | object | Yes |  |

## Nested Fields

### `user`

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
| `id` | integer (int64) | Yes |  |
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

