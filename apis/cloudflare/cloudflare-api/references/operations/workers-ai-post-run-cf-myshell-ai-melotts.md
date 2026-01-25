# POST /accounts/{account_id}/ai/run/@cf/myshell-ai/melotts

**Resource:** [Workers AI Text To Speech](../resources/Workers-AI-Text-To-Speech.md)
**Execute @cf/myshell-ai/melotts model.**
**Operation ID:** `workers-ai-post-run-cf-myshell-ai-melotts`

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
