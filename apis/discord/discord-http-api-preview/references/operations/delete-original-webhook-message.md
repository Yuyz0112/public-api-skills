# DELETE /webhooks/{webhook_id}/{webhook_token}/messages/@original

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `delete_original_webhook_message`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `thread_id` | query | SnowflakeType | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for delete_original_webhook_message |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
