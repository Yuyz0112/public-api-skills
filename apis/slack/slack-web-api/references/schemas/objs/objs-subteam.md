# objs_subteam

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `auto_provision` | boolean | Yes |  |
| `auto_type` | any | Yes |  |
| `channel_count` | integer | No |  |
| `created_by` | [defs_user_id](defs-user-id.md) | Yes |  |
| `date_create` | integer | Yes |  |
| `date_delete` | integer | Yes |  |
| `date_update` | integer | Yes |  |
| `deleted_by` | any | Yes |  |
| `description` | string | Yes |  |
| `enterprise_subteam_id` | string | Yes |  |
| `handle` | string | Yes |  |
| `id` | [defs_subteam_id](defs-subteam-id.md) | Yes |  |
| `is_external` | boolean | Yes |  |
| `is_subteam` | boolean | Yes |  |
| `is_usergroup` | boolean | Yes |  |
| `name` | string | Yes |  |
| `prefs` | object | Yes |  |
| `team_id` | [defs_team](defs-team.md) | Yes |  |
| `updated_by` | [defs_user_id](defs-user-id.md) | Yes |  |
| `user_count` | integer | No |  |
| `users` | defs_user_id[] | No |  |

## Nested Fields

### `prefs`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channels` | defs_channel_id[] | Yes |  |
| `groups` | defs_group_id[] | Yes |  |

