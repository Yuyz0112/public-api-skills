# POST /accounts/{account_id}/ai/run/@cf/ai4bharat/indictrans2-en-indic-1B

**Resource:** [Workers AI Translation](../resources/Workers-AI-Translation.md)
**Execute @cf/ai4bharat/indictrans2-en-indic-1B model.**
**Operation ID:** `workers-ai-post-run-cf-ai4bharat-indictrans2-en-indic-1B`

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
