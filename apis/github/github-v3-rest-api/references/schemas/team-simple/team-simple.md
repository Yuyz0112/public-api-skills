# team-simple

Groups of organization members that gives permissions on specified repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the team |
| `node_id` | string | Yes |  |
| `url` | string (uri) | Yes | URL for the team |
| `members_url` | string | Yes |  |
| `name` | string | Yes | Name of the team |
| `description` | string | Yes | Description of the team |
| `permission` | string | Yes | Permission that the team will have for its repositories |
| `privacy` | string | No | The level of privacy this team should have |
| `notification_setting` | string | No | The notification setting the team has set |
| `html_url` | string (uri) | Yes |  |
| `repositories_url` | string (uri) | Yes |  |
| `slug` | string | Yes |  |
| `ldap_dn` | string | No | Distinguished Name (DN) that team maps to within LDAP environment |
| `type` | enum: enterprise, organization | Yes | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |

