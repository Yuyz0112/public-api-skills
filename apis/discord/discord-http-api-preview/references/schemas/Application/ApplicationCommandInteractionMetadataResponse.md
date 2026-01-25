# ApplicationCommandInteractionMetadataResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | enum: 2 | Yes |  |
| `user` | [UserResponse](UserResponse.md) | No |  |
| `authorizing_integration_owners` | object | Yes |  |
| `original_response_message_id` | [SnowflakeType](SnowflakeType.md) | No |  |
| `target_user` | [UserResponse](UserResponse.md) | No |  |
| `target_message_id` | [SnowflakeType](SnowflakeType.md) | No |  |

