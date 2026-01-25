# POST /webhooks/{webhook_id}/{webhook_token}/slack

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `execute_slack_compatible_webhook`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `wait` | query | boolean | No |  |
| `thread_id` | query | SnowflakeType | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`, `application/x-www-form-urlencoded`, `multipart/form-data`

**Schema:** [SlackWebhook](../schemas/Slack/SlackWebhook.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for execute_slack_compatible_webhook |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
