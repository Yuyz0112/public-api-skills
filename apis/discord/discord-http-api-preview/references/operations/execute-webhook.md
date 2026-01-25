# POST /webhooks/{webhook_id}/{webhook_token}

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `execute_webhook`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `wait` | query | boolean | No |  |
| `thread_id` | query | SnowflakeType | No |  |
| `with_components` | query | boolean | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for execute_webhook |
| 204 | 204 response for execute_webhook |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[MessageResponse](../schemas/Message/MessageResponse.md)

## Security

- **BotToken**
