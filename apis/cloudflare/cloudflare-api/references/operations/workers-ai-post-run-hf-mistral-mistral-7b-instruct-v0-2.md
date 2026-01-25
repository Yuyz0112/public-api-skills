# POST /accounts/{account_id}/ai/run/@hf/mistral/mistral-7b-instruct-v0.2

**Resource:** [Workers AI Text Generation](../resources/Workers-AI-Text-Generation.md)
**Execute @hf/mistral/mistral-7b-instruct-v0.2 model.**
**Operation ID:** `workers-ai-post-run-hf-mistral-mistral-7b-instruct-v0-2`

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
