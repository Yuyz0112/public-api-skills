# team-role-assignment

The Relationship a Team has with a role.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `assignment` | enum: direct, indirect, mixed | No | Determines if the team has a direct, indirect, or mixed relationship to a role |
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
| `parent` | [nullable-team-simple](nullable-team-simple.md) | Yes |  |
| `type` | enum: enterprise, organization | Yes | The ownership type of the team |
| `organization_id` | integer | No | Unique identifier of the organization to which this team belongs |
| `enterprise_id` | integer | No | Unique identifier of the enterprise to which this team belongs |

## Nested Fields

### `permissions`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pull` | boolean | Yes |  |
| `triage` | boolean | Yes |  |
| `push` | boolean | Yes |  |
| `maintain` | boolean | Yes |  |
| `admin` | boolean | Yes |  |

