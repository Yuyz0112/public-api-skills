# GET /channels/{channel_id}/thread-members

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `list_thread_members`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_member` | query | boolean | No |  |
| `limit` | query | integer | No |  |
| `after` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for list_thread_members |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

Array of [ThreadMemberResponse](../schemas/Thread/ThreadMemberResponse.md)

## Security

- **BotToken**
