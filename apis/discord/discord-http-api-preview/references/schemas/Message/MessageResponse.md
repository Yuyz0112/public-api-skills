# MessageResponse

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
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `channel_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `author` | [UserResponse](UserResponse.md) | Yes |  |
| `pinned` | boolean | Yes |  |
| `mention_everyone` | boolean | Yes |  |
| `tts` | boolean | Yes |  |
| `call` | [MessageCallResponse](MessageCallResponse.md) | No |  |
| `activity` | [MessageActivityResponse](MessageActivityResponse.md) | No |  |
| `application` | [BasicApplicationResponse](BasicApplicationResponse.md) | No |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `interaction` | [MessageInteractionResponse](MessageInteractionResponse.md) | No |  |
| `nonce` | any | No |  |
| `webhook_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `message_reference` | [MessageReferenceResponse](MessageReferenceResponse.md) | No |  |
| `thread` | [ThreadResponse](ThreadResponse.md) | No |  |
| `mention_channels` | any[] | No |  |
| `role_subscription_data` | [MessageRoleSubscriptionDataResponse](MessageRoleSubscriptionDataResponse.md) | No |  |
| `purchase_notification` | [PurchaseNotificationResponse](PurchaseNotificationResponse.md) | No |  |
| `position` | integer (int32) | No |  |
| `resolved` | [ResolvedObjectsResponse](ResolvedObjectsResponse.md) | No |  |
| `poll` | [PollResponse](PollResponse.md) | No |  |
| `shared_client_theme` | any | No |  |
| `interaction_metadata` | any | No |  |
| `message_snapshots` | MessageSnapshotResponse[] | No |  |
| `reactions` | MessageReactionResponse[] | No |  |
| `referenced_message` | any | No |  |

