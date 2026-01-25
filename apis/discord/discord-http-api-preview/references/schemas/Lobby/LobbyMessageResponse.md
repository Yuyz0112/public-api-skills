# LobbyMessageResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | [MessageType](MessageType.md) | Yes |  |
| `content` | string | Yes |  |
| `lobby_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `channel_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `author` | [UserResponse](UserResponse.md) | Yes |  |
| `metadata` | object | No |  |
| `flags` | integer (int32) | Yes |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | No |  |

