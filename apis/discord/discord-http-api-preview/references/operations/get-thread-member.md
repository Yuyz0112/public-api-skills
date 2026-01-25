# GET /channels/{channel_id}/thread-members/{user_id}

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `get_thread_member`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `with_member` | query | boolean | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_thread_member |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[ThreadMemberResponse](../schemas/Thread/ThreadMemberResponse.md)

## Security

- **BotToken**
