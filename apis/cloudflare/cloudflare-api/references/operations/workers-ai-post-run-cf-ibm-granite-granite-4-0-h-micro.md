# POST /accounts/{account_id}/ai/run/@cf/ibm-granite/granite-4.0-h-micro

**Resource:** [Workers AI Text Generation](../resources/Workers-AI-Text-Generation.md)
**Execute @cf/ibm-granite/granite-4.0-h-micro model.**
**Operation ID:** `workers-ai-post-run-cf-ibm-granite-granite-4-0-h-micro`

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
