# enterprise-team

Group of enterprise owners and/or members

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `name` | string | Yes |  |
| `description` | string | No |  |
| `slug` | string | Yes |  |
| `url` | string (uri) | Yes |  |
| `sync_to_organizations` | string | No | Retired: this field will not be returned with GHEC enterprise teams. |
| `organization_selection_type` | string | No |  |
| `group_id` | string | Yes |  |
| `group_name` | string | No | Retired: this field will not be returned with GHEC enterprise teams. |
| `html_url` | string (uri) | Yes |  |
| `members_url` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |

