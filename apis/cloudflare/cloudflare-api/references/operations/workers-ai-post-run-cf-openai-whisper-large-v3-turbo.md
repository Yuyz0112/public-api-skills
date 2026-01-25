# POST /accounts/{account_id}/ai/run/@cf/openai/whisper-large-v3-turbo

**Resource:** [Workers AI Automatic Speech Recognition](../resources/Workers-AI-Automatic-Speech-Recognition.md)
**Execute @cf/openai/whisper-large-v3-turbo model.**
**Operation ID:** `workers-ai-post-run-cf-openai-whisper-large-v3-turbo`

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
