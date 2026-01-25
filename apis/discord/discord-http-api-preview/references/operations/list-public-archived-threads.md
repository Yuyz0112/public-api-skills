# GET /channels/{channel_id}/threads/archived/public

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_public_archived_threads`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `before` | query | string (date-time) | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_public_archived_threads |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadsResponse](../schemas/Threads/ThreadsResponse.md)

## Security

- **BotToken**
