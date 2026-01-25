# GroupDMInviteResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: 1 | Yes |  |
| `code` | string | Yes |  |
| `inviter` | [UserResponse](UserResponse.md) | No |  |
| `max_age` | integer (int32) | No |  |
| `created_at` | string (date-time) | No |  |
| `expires_at` | string,null (date-time) | No |  |
| `channel` | [InviteChannelResponse](InviteChannelResponse.md) | Yes |  |
| `approximate_member_count` | integer,null (int32) | No |  |

