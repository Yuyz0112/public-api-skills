# APIEntitiesRemoteMirror

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `enabled` | Boolean | No |  |
| `url` | string | No |  |
| `update_status` | string | No |  |
| `last_update_at` | DateTime | No |  |
| `last_update_started_at` | DateTime | No |  |
| `last_successful_update_at` | DateTime | No |  |
| `last_error` | integer | No |  |
| `only_protected_branches` | Boolean | No |  |
| `keep_divergent_refs` | Boolean | No |  |
| `auth_method` | string | No |  |
| `host_keys` | APIEntitiesMirrorHostKey[] | No |  |
| `mirror_branch_regex` | string | No |  |

