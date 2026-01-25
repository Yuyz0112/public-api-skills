# POST /channels/{channel_id}/followers

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `follow_channel`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for follow_channel |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ChannelFollowerResponse](../schemas/Channel/ChannelFollowerResponse.md)

## Security

- **BotToken**
