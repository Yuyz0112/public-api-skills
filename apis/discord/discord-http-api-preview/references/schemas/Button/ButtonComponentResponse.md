# ButtonComponentResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 2 | Yes |  |
| `id` | integer (int32) | Yes |  |
| `custom_id` | string | No |  |
| `style` | [ButtonStyleTypes](ButtonStyleTypes.md) | Yes |  |
| `label` | string | No |  |
| `disabled` | boolean | No |  |
| `emoji` | [ComponentEmojiResponse](ComponentEmojiResponse.md) | No |  |
| `url` | string,null (uri) | No |  |
| `sku_id` | [SnowflakeType](SnowflakeType.md) | No |  |

