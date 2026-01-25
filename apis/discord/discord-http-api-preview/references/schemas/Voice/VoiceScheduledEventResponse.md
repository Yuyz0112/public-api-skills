# VoiceScheduledEventResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `channel_id` | any | No |  |
| `creator_id` | any | No |  |
| `creator` | [UserResponse](UserResponse.md) | No |  |
| `image` | string,null | No |  |
| `scheduled_start_time` | string (date-time) | Yes |  |
| `scheduled_end_time` | string,null (date-time) | No |  |
| `status` | [GuildScheduledEventStatuses](GuildScheduledEventStatuses.md) | Yes |  |
| `entity_type` | enum: 2 | Yes |  |
| `entity_id` | any | No |  |
| `user_count` | integer (int32) | No |  |
| `privacy_level` | [GuildScheduledEventPrivacyLevels](GuildScheduledEventPrivacyLevels.md) | Yes |  |
| `user_rsvp` | any | No |  |
| `entity_metadata` | any | No |  |

