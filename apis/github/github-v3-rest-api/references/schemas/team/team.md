# team

Groups of organization members that gives permissions on specified repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `name` | string | Yes |  |
| `slug` | string | Yes |  |
| `description` | string | Yes |  |
| `privacy` | string | No |  |
| `notification_setting` | string | No |  |
| `permission` | string | Yes |  |
| `permissions` | object | No |  |
| `url` | string (uri) | Yes |  |
| `html_url` | string (uri) | Yes |  |
| `members_url` | string | Yes |  |
| `repositories_url` | string (uri) | Yes |  |
| `type` | enum: enterprise, organization | Yes | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |
| `parent` | [nullable-team-simple](nullable-team-simple.md) | Yes |  |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pull` | boolean | Yes |  |
| `triage` | boolean | Yes |  |
| `push` | boolean | Yes |  |
| `maintain` | boolean | Yes |  |
| `admin` | boolean | Yes |  |

