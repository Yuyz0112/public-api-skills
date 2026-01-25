# GuildPreviewResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `icon` | string,null | No |  |
| `description` | string,null | No |  |
| `home_header` | string,null | No |  |
| `splash` | string,null | No |  |
| `discovery_splash` | string,null | No |  |
| `features` | GuildFeatures[] | Yes |  |
| `approximate_member_count` | integer (int32) | Yes |  |
| `approximate_presence_count` | integer (int32) | Yes |  |
| `emojis` | EmojiResponse[] | Yes |  |
| `stickers` | GuildStickerResponse[] | Yes |  |

