# KeywordRuleResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `guild_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `creator_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `event_type` | [AutomodEventType](AutomodEventType.md) | Yes |  |
| `actions` | any[] | Yes |  |
| `trigger_type` | enum: 1 | Yes |  |
| `enabled` | boolean | Yes |  |
| `exempt_roles` | SnowflakeType[] | Yes |  |
| `exempt_channels` | SnowflakeType[] | Yes |  |
| `trigger_metadata` | [KeywordTriggerMetadataResponse](KeywordTriggerMetadataResponse.md) | Yes |  |

