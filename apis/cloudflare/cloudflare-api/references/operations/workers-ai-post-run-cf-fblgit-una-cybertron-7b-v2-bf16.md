# POST /accounts/{account_id}/ai/run/@cf/fblgit/una-cybertron-7b-v2-bf16

**Resource:** [Workers AI Text Generation](../resources/Workers-AI-Text-Generation.md)
**Execute @cf/fblgit/una-cybertron-7b-v2-bf16 model.**
**Operation ID:** `workers-ai-post-run-cf-fblgit-una-cybertron-7b-v2-bf16`

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
