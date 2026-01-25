# FriendInviteResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 2 | Yes |  |
| `code` | string | Yes |  |
| `inviter` | [UserResponse](UserResponse.md) | No |  |
| `max_age` | integer (int32) | No |  |
| `created_at` | string (date-time) | No |  |
| `expires_at` | string,null (date-time) | No |  |
| `friends_count` | integer (int32) | No |  |
| `channel` | any | No |  |
| `is_contact` | boolean | No |  |
| `uses` | integer (int32) | No |  |
| `max_uses` | integer (int32) | No |  |
| `flags` | integer (int32) | No |  |

