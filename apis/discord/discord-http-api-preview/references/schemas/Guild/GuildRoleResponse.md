# GuildRoleResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `permissions` | string | Yes |  |
| `position` | integer (int32) | Yes |  |
| `color` | integer (int32) | Yes |  |
| `colors` | [GuildRoleColorsResponse](GuildRoleColorsResponse.md) | Yes |  |
| `hoist` | boolean | Yes |  |
| `managed` | boolean | Yes |  |
| `mentionable` | boolean | Yes |  |
| `icon` | string,null | No |  |
| `unicode_emoji` | string,null | No |  |
| `tags` | [GuildRoleTagsResponse](GuildRoleTagsResponse.md) | No |  |
| `flags` | integer (int32) | Yes |  |

