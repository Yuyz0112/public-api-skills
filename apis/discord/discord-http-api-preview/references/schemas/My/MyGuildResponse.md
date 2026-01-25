# MyGuildResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `icon` | string,null | No |  |
| `banner` | string,null | No |  |
| `owner` | boolean | Yes |  |
| `permissions` | string | Yes |  |
| `features` | GuildFeatures[] | Yes |  |
| `approximate_member_count` | integer,null (int32) | No |  |
| `approximate_presence_count` | integer,null (int32) | No |  |

