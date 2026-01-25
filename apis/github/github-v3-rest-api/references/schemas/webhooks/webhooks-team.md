# webhooks_team

Groups of organization members that gives permissions on specified repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deleted` | boolean | No |  |
| `description` | string | No | Description of the team |
| `html_url` | string (uri) | No |  |
| `id` | integer | Yes | Unique identifier of the team |
| `members_url` | string (uri-template) | No |  |
| `name` | string | Yes | Name of the team |
| `node_id` | string | No |  |
| `parent` | object | No |  |
| `permission` | string | No | Permission that the team will have for its repositories |
| `privacy` | enum: open, closed, secret | No |  |
| `notification_setting` | enum: notifications_enabled, notifications_disabled | No |  |
| `repositories_url` | string (uri) | No |  |
| `slug` | string | No |  |
| `url` | string (uri) | No | URL for the team |
| `type` | enum: enterprise, organization | No | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |

## Nested Fields

### `parent`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | Description of the team |
| `html_url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the team |
| `members_url` | string (uri-template) | Yes |  |
| `name` | string | Yes | Name of the team |
| `node_id` | string | Yes |  |
| `permission` | string | Yes | Permission that the team will have for its repositories |
| `privacy` | enum: open, closed, secret | Yes |  |
| `notification_setting` | enum: notifications_enabled, notifications_disabled | Yes | Whether team members will receive notifications when their team is @mentioned |
| `repositories_url` | string (uri) | Yes |  |
| `slug` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the team |
| `type` | enum: enterprise, organization | Yes | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |

