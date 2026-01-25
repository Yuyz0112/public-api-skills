# POST /accounts/{account_id}/ai/run/@cf/deepgram/flux

**Resource:** [Workers AI Automatic Speech Recognition](../resources/Workers-AI-Automatic-Speech-Recognition.md)
**Execute @cf/deepgram/flux model.**
**Operation ID:** `workers-ai-post-run-cf-deepgram-flux`

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
