# GuildChannelResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | enum: 0, 2, 4... | Yes |  |
| `last_message_id` | any | No |  |
| `flags` | integer (int32) | Yes |  |
| `last_pin_timestamp` | string,null (date-time) | No |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `parent_id` | any | No |  |
| `rate_limit_per_user` | integer (int32) | No |  |
| `bitrate` | integer (int32) | No |  |
| `user_limit` | integer (int32) | No |  |
| `rtc_region` | string,null | No |  |
| `video_quality_mode` | [VideoQualityModes](VideoQualityModes.md) | No |  |
| `permissions` | string,null | No |  |
| `topic` | string,null | No |  |
| `default_auto_archive_duration` | [ThreadAutoArchiveDuration](ThreadAutoArchiveDuration.md) | No |  |
| `default_thread_rate_limit_per_user` | integer (int32) | No |  |
| `position` | integer (int32) | Yes |  |
| `permission_overwrites` | ChannelPermissionOverwriteResponse[] | No |  |
| `nsfw` | boolean | No |  |
| `available_tags` | ForumTagResponse[] | No |  |
| `default_reaction_emoji` | any | No |  |
| `default_sort_order` | any | No |  |
| `default_forum_layout` | any | No |  |
| `default_tag_setting` | any | No |  |
| `hd_streaming_until` | string (date-time) | No |  |
| `hd_streaming_buyer_id` | [SnowflakeType](SnowflakeType.md) | No |  |

