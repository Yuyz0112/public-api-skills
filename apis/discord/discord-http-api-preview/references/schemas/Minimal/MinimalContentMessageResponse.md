# MinimalContentMessageResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | [MessageType](MessageType.md) | Yes |  |
| `content` | string | Yes |  |
| `mentions` | UserResponse[] | Yes |  |
| `mention_roles` | SnowflakeType[] | Yes |  |
| `attachments` | MessageAttachmentResponse[] | Yes |  |
| `embeds` | MessageEmbedResponse[] | Yes |  |
| `timestamp` | string (date-time) | Yes |  |
| `edited_timestamp` | string,null (date-time) | No |  |
| `flags` | integer (int32) | Yes |  |
| `components` | any[] | Yes |  |
| `stickers` | any[] | No |  |
| `sticker_items` | MessageStickerItemResponse[] | No |  |

