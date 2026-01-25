# GET /channels/{channel_id}/messages/pins

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_pins`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `before` | query | string (date-time) | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_pins |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[PinnedMessagesResponse](../schemas/Pinned/PinnedMessagesResponse.md)

## Security

- **BotToken**
