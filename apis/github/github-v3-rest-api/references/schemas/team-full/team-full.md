# team-full

Groups of organization members that gives permissions on specified repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the team |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the team |
| `html_url` | string (uri) | Yes |  |
| `name` | string | Yes | Name of the team |
| `slug` | string | Yes |  |
| `description` | string | Yes |  |
| `privacy` | enum: closed, secret | No | The level of privacy this team should have |
| `notification_setting` | enum: notifications_enabled, notifications_disabled | No | The notification setting the team has set |
| `permission` | string | Yes | Permission that the team will have for its repositories |
| `members_url` | string | Yes |  |
| `repositories_url` | string (uri) | Yes |  |
| `parent` | [nullable-team-simple](nullable-team-simple.md) | No |  |
| `members_count` | integer | Yes |  |
| `repos_count` | integer | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `organization` | [team-organization](team-organization.md) | Yes |  |
| `ldap_dn` | [ldap-dn](ldap-dn.md) | No |  |
| `type` | enum: enterprise, organization | Yes | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |

