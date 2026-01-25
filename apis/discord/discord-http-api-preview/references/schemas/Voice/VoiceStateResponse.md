# VoiceStateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `channel_id` | any | No |  |
| `deaf` | boolean | Yes |  |
| `guild_id` | any | No |  |
| `member` | [GuildMemberResponse](GuildMemberResponse.md) | No |  |
| `mute` | boolean | Yes |  |
| `request_to_speak_timestamp` | string,null (date-time) | No |  |
| `suppress` | boolean | Yes |  |
| `self_stream` | boolean,null | No |  |
| `self_deaf` | boolean | Yes |  |
| `self_mute` | boolean | Yes |  |
| `self_video` | boolean | Yes |  |
| `session_id` | string | Yes |  |
| `user_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |

