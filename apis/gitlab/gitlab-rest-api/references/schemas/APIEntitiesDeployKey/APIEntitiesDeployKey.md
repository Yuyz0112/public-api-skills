# APIEntitiesDeployKey

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `title` | string | No |  |
| `created_at` | DateTime | No |  |
| `expires_at` | DateTime | No |  |
| `last_used_at` | DateTime | No |  |
| `key` | string | No |  |
| `usage_type` | string | No |  |
| `fingerprint` | string | No |  |
| `fingerprint_sha256` | string | No |  |
| `projects_with_write_access` | [APIEntitiesProjectIdentity](APIEntitiesProjectIdentity.md) | No |  |
| `projects_with_readonly_access` | [APIEntitiesProjectIdentity](APIEntitiesProjectIdentity.md) | No |  |

