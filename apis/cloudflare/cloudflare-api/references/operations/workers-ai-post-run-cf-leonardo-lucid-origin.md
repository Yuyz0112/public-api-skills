# POST /accounts/{account_id}/ai/run/@cf/leonardo/lucid-origin

**Resource:** [Workers AI Text To Image](../resources/Workers-AI-Text-To-Image.md)
**Execute @cf/leonardo/lucid-origin model.**
**Operation ID:** `workers-ai-post-run-cf-leonardo-lucid-origin`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `queueRequest` | query | string | No |  |
| `tags` | query | string | No |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Object with user data. |
| 400 | Bad request |

## Security

- **api_token**
- **api_email**
- **api_key**
