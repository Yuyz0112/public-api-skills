# GET /channels/{channel_id}/messages

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_messages`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `around` | query | SnowflakeType | No |  |
| `before` | query | SnowflakeType | No |  |
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_messages |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
