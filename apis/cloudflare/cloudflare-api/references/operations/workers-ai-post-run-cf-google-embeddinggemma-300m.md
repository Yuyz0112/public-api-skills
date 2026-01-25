# POST /accounts/{account_id}/ai/run/@cf/google/embeddinggemma-300m

**Resource:** [Workers AI Text Embeddings](../resources/Workers-AI-Text-Embeddings.md)
**Execute @cf/google/embeddinggemma-300m model.**
**Operation ID:** `workers-ai-post-run-cf-google-embeddinggemma-300m`

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
