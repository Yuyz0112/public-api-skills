# POST /accounts/{account_id}/ai/run/@cf/qwen/qwen1.5-7b-chat-awq

**Resource:** [Workers AI Text Generation](../resources/Workers-AI-Text-Generation.md)
**Execute @cf/qwen/qwen1.5-7b-chat-awq model.**
**Operation ID:** `workers-ai-post-run-cf-qwen-qwen1-5-7b-chat-awq`

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
