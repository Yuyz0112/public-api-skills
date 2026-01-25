# POST /accounts/{account_id}/ai/run/@cf/facebook/bart-large-cnn

**Resource:** [Workers AI Summarization](../resources/Workers-AI-Summarization.md)
**Execute @cf/facebook/bart-large-cnn model.**
**Operation ID:** `workers-ai-post-run-cf-facebook-bart-large-cnn`

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
