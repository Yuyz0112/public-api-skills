# GuildTemplateResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `code` | string | Yes |  |
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `usage_count` | integer (int32) | Yes |  |
| `creator_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `creator` | any | No |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `source_guild_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `serialized_source_guild` | [GuildTemplateSnapshotResponse](GuildTemplateSnapshotResponse.md) | Yes |  |
| `is_dirty` | boolean,null | No |  |

