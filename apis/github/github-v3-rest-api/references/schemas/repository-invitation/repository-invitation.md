# repository-invitation

Repository invitations let you manage who you collaborate with.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | Unique identifier of the repository invitation. |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `invitee` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `inviter` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `permissions` | enum: read, write, admin... | Yes | The permission associated with the invitation. |
| `created_at` | string (date-time) | Yes |  |
| `expired` | boolean | No | Whether or not the invitation has expired |
| `url` | string | Yes | URL for the repository invitation |
| `html_url` | string | Yes |  |
| `node_id` | string | Yes |  |

