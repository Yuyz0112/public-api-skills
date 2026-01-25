# objs_message

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `attachments` | object[] | No |  |
| `blocks` | [blocks](blocks.md) | No |  |
| `bot_id` | any | No |  |
| `bot_profile` | [objs_bot_profile](objs-bot-profile.md) | No |  |
| `client_msg_id` | string | No |  |
| `comment` | [objs_comment](objs-comment.md) | No |  |
| `display_as_bot` | boolean | No |  |
| `file` | [objs_file](objs-file.md) | No |  |
| `files` | objs_file[] | No |  |
| `icons` | object | No |  |
| `inviter` | [defs_user_id](defs-user-id.md) | No |  |
| `is_delayed_message` | boolean | No |  |
| `is_intro` | boolean | No |  |
| `is_starred` | boolean | No |  |
| `last_read` | [defs_ts](defs-ts.md) | No |  |
| `latest_reply` | [defs_ts](defs-ts.md) | No |  |
| `name` | string | No |  |
| `old_name` | string | No |  |
| `parent_user_id` | [defs_user_id](defs-user-id.md) | No |  |
| `permalink` | string (uri) | No |  |
| `pinned_to` | defs_channel[] | No |  |
| `purpose` | string | No |  |
| `reactions` | objs_reaction[] | No |  |
| `reply_count` | integer | No |  |
| `reply_users` | defs_user_id[] | No |  |
| `reply_users_count` | integer | No |  |
| `source_team` | [defs_workspace_id](defs-workspace-id.md) | No |  |
| `subscribed` | boolean | No |  |
| `subtype` | string | No |  |
| `team` | [defs_workspace_id](defs-workspace-id.md) | No |  |
| `text` | string | Yes |  |
| `thread_ts` | [defs_ts](defs-ts.md) | No |  |
| `topic` | string | No |  |
| `ts` | [defs_ts](defs-ts.md) | Yes |  |
| `type` | string | Yes |  |
| `unread_count` | integer | No |  |
| `upload` | boolean | No |  |
| `user` | [defs_user_id](defs-user-id.md) | No |  |
| `user_profile` | [objs_user_profile_short](objs-user-profile-short.md) | No |  |
| `user_team` | [defs_workspace_id](defs-workspace-id.md) | No |  |
| `username` | string | No |  |

## Nested Fields

### `attachments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `fallback` | string | No |  |
| `id` | integer | Yes |  |
| `image_bytes` | integer | No |  |
| `image_height` | integer | No |  |
| `image_url` | string | No |  |
| `image_width` | integer | No |  |

### `icons`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `emoji` | string | No |  |
| `image_64` | string (uri) | No |  |

