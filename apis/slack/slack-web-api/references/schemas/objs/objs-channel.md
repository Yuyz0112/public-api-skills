# objs_channel

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `accepted_user` | [defs_user_id](defs-user-id.md) | No |  |
| `created` | integer | Yes |  |
| `creator` | [defs_user_id](defs-user-id.md) | Yes |  |
| `id` | [defs_channel_id](defs-channel-id.md) | Yes |  |
| `is_archived` | boolean | No |  |
| `is_channel` | boolean | Yes |  |
| `is_frozen` | boolean | No |  |
| `is_general` | boolean | No |  |
| `is_member` | boolean | No |  |
| `is_moved` | integer | No |  |
| `is_mpim` | boolean | Yes |  |
| `is_non_threadable` | boolean | No |  |
| `is_org_shared` | boolean | Yes |  |
| `is_pending_ext_shared` | boolean | No |  |
| `is_private` | boolean | Yes |  |
| `is_read_only` | boolean | No |  |
| `is_shared` | boolean | Yes |  |
| `is_thread_only` | boolean | No |  |
| `last_read` | [defs_ts](defs-ts.md) | No |  |
| `latest` | any | No |  |
| `members` | defs_user_id[] | Yes |  |
| `name` | string | Yes |  |
| `name_normalized` | string | Yes |  |
| `num_members` | integer | No |  |
| `pending_shared` | defs_team[] | No |  |
| `previous_names` | defs_channel_name[] | No |  |
| `priority` | number | No |  |
| `purpose` | object | Yes |  |
| `topic` | object | Yes |  |
| `unlinked` | integer | No |  |
| `unread_count` | integer | No |  |
| `unread_count_display` | integer | No |  |

## Nested Fields

### `purpose`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `creator` | [defs_topic_purpose_creator](defs-topic-purpose-creator.md) | Yes |  |
| `last_set` | integer | Yes |  |
| `value` | string | Yes |  |

### `topic`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `creator` | [defs_topic_purpose_creator](defs-topic-purpose-creator.md) | Yes |  |
| `last_set` | integer | Yes |  |
| `value` | string | Yes |  |

