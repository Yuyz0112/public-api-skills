# POST /accounts/{account_id}/ai/run/@cf/qwen/qwen3-embedding-0.6b

**Resource:** [Workers AI Text Embeddings](../resources/Workers-AI-Text-Embeddings.md)
**Execute @cf/qwen/qwen3-embedding-0.6b model.**
**Operation ID:** `workers-ai-post-run-cf-qwen-qwen3-embedding-0-6b`

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
