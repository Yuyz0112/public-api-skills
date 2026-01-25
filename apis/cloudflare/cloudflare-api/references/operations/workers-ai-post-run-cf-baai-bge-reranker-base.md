# POST /accounts/{account_id}/ai/run/@cf/baai/bge-reranker-base

**Resource:** [Workers AI Text Classification](../resources/Workers-AI-Text-Classification.md)
**Execute @cf/baai/bge-reranker-base model.**
**Operation ID:** `workers-ai-post-run-cf-baai-bge-reranker-base`

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
