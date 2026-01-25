# PrivateChannelResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | [SnowflakeType](SnowflakeType.md) | Yes |  |
| `type` | enum: 1 | Yes |  |
| `last_message_id` | any | No |  |
| `flags` | integer (int32) | Yes |  |
| `last_pin_timestamp` | string,null (date-time) | No |  |
| `recipients` | UserResponse[] | Yes |  |

