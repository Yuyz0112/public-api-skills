# GuildTemplateChannelResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer,null (int32) | No |  |
| `type` | enum: 0, 2, 4... | Yes |  |
| `name` | string,null | No |  |
| `position` | integer,null (int32) | No |  |
| `topic` | string,null | No |  |
| `bitrate` | integer (int32) | Yes |  |
| `user_limit` | integer (int32) | Yes |  |
| `nsfw` | boolean | Yes |  |
| `rate_limit_per_user` | integer (int32) | Yes |  |
| `parent_id` | any | No |  |
| `default_auto_archive_duration` | any | No |  |
| `permission_overwrites` | any[] | Yes |  |
| `available_tags` | array,null | No |  |
| `template` | string | Yes |  |
| `default_reaction_emoji` | any | No |  |
| `default_thread_rate_limit_per_user` | integer,null (int32) | No |  |
| `default_sort_order` | any | No |  |
| `default_forum_layout` | any | No |  |
| `default_tag_setting` | any | No |  |
| `icon_emoji` | any | No |  |
| `theme_color` | integer,null (int32) | No |  |

