# StageScheduledEventCreateRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `image` | string,null | No |  |
| `scheduled_start_time` | string (date-time) | Yes |  |
| `scheduled_end_time` | string,null (date-time) | No |  |
| `privacy_level` | [GuildScheduledEventPrivacyLevels](GuildScheduledEventPrivacyLevels.md) | Yes |  |
| `entity_type` | enum: 1 | Yes |  |
| `channel_id` | any | No |  |
| `entity_metadata` | any | No |  |

