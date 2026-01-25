# GET /channels/{channel_id}/messages/{message_id}/reactions/{emoji_name}

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_message_reactions_by_emoji`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |
| `type` | query | ReactionTypes | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_message_reactions_by_emoji |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [UserResponse](../schemas/User/UserResponse.md)

## Security

- **BotToken**
