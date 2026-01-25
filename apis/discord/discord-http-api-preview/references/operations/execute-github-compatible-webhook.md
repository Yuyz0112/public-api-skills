# POST /webhooks/{webhook_id}/{webhook_token}/github

**Resource:** [webhooks](../resources/webhooks.md)
**Operation ID:** `execute_github_compatible_webhook`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `wait` | query | boolean | No |  |
| `thread_id` | query | SnowflakeType | No |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [GithubWebhook](../schemas/Github/GithubWebhook.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for execute_github_compatible_webhook |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
