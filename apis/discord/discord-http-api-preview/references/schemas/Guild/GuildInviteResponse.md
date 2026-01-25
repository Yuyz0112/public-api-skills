# GuildInviteResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 0 | Yes |  |
| `code` | string | Yes |  |
| `inviter` | [UserResponse](UserResponse.md) | No |  |
| `max_age` | integer (int32) | No |  |
| `created_at` | string (date-time) | No |  |
| `expires_at` | string,null (date-time) | No |  |
| `is_contact` | boolean | No |  |
| `flags` | integer (int32) | No |  |
| `guild` | [InviteGuildResponse](InviteGuildResponse.md) | Yes |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `channel` | [InviteChannelResponse](InviteChannelResponse.md) | Yes |  |
| `target_type` | [InviteTargetTypes](InviteTargetTypes.md) | No |  |
| `target_user` | [UserResponse](UserResponse.md) | No |  |
| `target_application` | [InviteApplicationResponse](InviteApplicationResponse.md) | No |  |
| `guild_scheduled_event` | [ScheduledEventResponse](ScheduledEventResponse.md) | No |  |
| `uses` | integer (int32) | No |  |
| `max_uses` | integer (int32) | No |  |
| `temporary` | boolean | No |  |
| `approximate_member_count` | integer,null (int32) | No |  |
| `approximate_presence_count` | integer,null (int32) | No |  |
| `is_nickname_changeable` | boolean | No |  |
| `roles` | array,null | No |  |

