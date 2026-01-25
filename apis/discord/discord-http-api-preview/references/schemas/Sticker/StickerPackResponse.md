# StickerPackResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `sku_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `name` | string | Yes |  |
| `description` | string,null | No |  |
| `stickers` | StandardStickerResponse[] | Yes |  |
| `cover_sticker_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `banner_asset_id` | [SnowflakeType](SnowflakeType.md) | No |  |

