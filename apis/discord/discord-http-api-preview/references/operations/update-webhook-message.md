# PATCH /webhooks/{webhook_id}/{webhook_token}/messages/{message_id}

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `update_webhook_message`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `thread_id` | query | SnowflakeType | No |  |
| `with_components` | query | boolean | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

**Schema:** [IncomingWebhookUpdateRequestPartial](../schemas/Incoming/IncomingWebhookUpdateRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_webhook_message |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**
