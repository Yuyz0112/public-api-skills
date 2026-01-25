# CreatedThreadResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | enum: 10, 11, 12 | Yes |  |
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
| `owner_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `thread_metadata` | [ThreadMetadataResponse](ThreadMetadataResponse.md) | Yes |  |
| `message_count` | integer (int32) | Yes |  |
| `member_count` | integer (int32) | Yes |  |
| `total_message_sent` | integer (int32) | Yes |  |
| `applied_tags` | SnowflakeType[] | No |  |
| `member` | [ThreadMemberResponse](ThreadMemberResponse.md) | No |  |

