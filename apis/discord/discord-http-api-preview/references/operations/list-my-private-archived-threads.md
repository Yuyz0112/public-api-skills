# GET /channels/{channel_id}/users/@me/threads/archived/private

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_my_private_archived_threads`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `before` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_my_private_archived_threads |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadsResponse](../schemas/Threads/ThreadsResponse.md)

## Security

- **BotToken**
