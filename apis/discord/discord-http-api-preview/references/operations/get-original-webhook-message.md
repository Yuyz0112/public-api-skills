# GET /webhooks/{webhook_id}/{webhook_token}/messages/@original

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `get_original_webhook_message`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `thread_id` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_original_webhook_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**
