# POST /accounts/{account_id}/ai/run/@cf/openai/whisper

**Resource:** [Workers AI Automatic Speech Recognition](../resources/Workers-AI-Automatic-Speech-Recognition.md)
**Execute @cf/openai/whisper model.**
**Operation ID:** `workers-ai-post-run-cf-openai-whisper`

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
