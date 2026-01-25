# organization-invitation

Organization Invitation

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `login` | string | Yes |  |
| `email` | string | Yes |  |
| `role` | string | Yes |  |
| `created_at` | string | Yes |  |
| `failed_at` | string | No |  |
| `failed_reason` | string | No |  |
| `inviter` | [simple-user](simple-user.md) | Yes |  |
| `team_count` | integer | Yes |  |
| `node_id` | string | Yes |  |
| `invitation_teams_url` | string | Yes |  |
| `invitation_source` | string | No |  |

