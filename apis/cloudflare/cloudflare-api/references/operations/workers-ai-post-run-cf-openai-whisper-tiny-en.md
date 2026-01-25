# POST /accounts/{account_id}/ai/run/@cf/openai/whisper-tiny-en

**Resource:** [Workers AI Automatic Speech Recognition](../resources/Workers-AI-Automatic-Speech-Recognition.md)
**Execute @cf/openai/whisper-tiny-en model.**
**Operation ID:** `workers-ai-post-run-cf-openai-whisper-tiny-en`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes |  |
| `queueRequest` | query | string | No |  |
| `tags` | query | string | No |  |

## Request Body

**Content Types:** `application/octet-stream`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Object with user data. |
| 400 | Bad request |

## Security

- **api_token**
- **api_email**
- **api_key**
