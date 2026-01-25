# PrivateGroupChannelResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | enum: 3 | Yes |  |
| `last_message_id` | any | No |  |
| `flags` | integer (int32) | Yes |  |
| `last_pin_timestamp` | string,null (date-time) | No |  |
| `recipients` | UserResponse[] | Yes |  |
| `name` | string,null | No |  |
| `icon` | string,null | No |  |
| `owner_id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `managed` | boolean | No |  |
| `application_id` | [SnowflakeType](SnowflakeType.md) | No |  |

