# user-role-assignment

The Relationship a User has with a role.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignment` | enum: direct, indirect, mixed | No | Determines if the user has a direct, indirect, or mixed relationship to a role |
| `inherited_from` | team-simple[] | No | Team the user has gotten the role through |
| `name` | string | No |  |
| `email` | string | No |  |
| `login` | string | Yes |  |
| `id` | integer | Yes |  |
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
| `starred_at` | string | No |  |
| `user_view_type` | string | No |  |

