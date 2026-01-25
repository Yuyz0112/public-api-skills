# GET /channels/{channel_id}/polls/{message_id}/answers/{answer_id}

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `get_answer_voters`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `after` | query | SnowflakeType | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_answer_voters |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[PollAnswerDetailsResponse](../schemas/Poll/PollAnswerDetailsResponse.md)

## Security

- **BotToken**
