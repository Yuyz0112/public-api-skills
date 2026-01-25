# PrivateGuildMemberResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatar` | string,null | No |  |
| `avatar_decoration_data` | any | No |  |
| `banner` | string,null | No |  |
| `communication_disabled_until` | string,null (date-time) | No |  |
| `flags` | integer (int32) | Yes |  |
| `joined_at` | string (date-time) | Yes |  |
| `nick` | string,null | No |  |
| `pending` | boolean | Yes |  |
| `premium_since` | string,null (date-time) | No |  |
| `roles` | SnowflakeType[] | Yes |  |
| `collectibles` | any | No |  |
| `user` | [UserResponse](UserResponse.md) | Yes |  |
| `mute` | boolean | Yes |  |
| `deaf` | boolean | Yes |  |
| `permissions` | string | No |  |

