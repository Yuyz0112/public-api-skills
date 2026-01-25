# LobbyResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `metadata` | object,null | No |  |
| `members` | LobbyMemberResponse[] | Yes |  |
| `linked_channel` | [GuildChannelResponse](GuildChannelResponse.md) | No |  |
| `flags` | [UInt32Type](UInt32Type.md) | Yes |  |
| `override_event_webhooks_url` | string,null | No |  |

