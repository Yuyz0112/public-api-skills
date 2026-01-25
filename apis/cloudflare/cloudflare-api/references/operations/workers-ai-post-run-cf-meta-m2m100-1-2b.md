# POST /accounts/{account_id}/ai/run/@cf/meta/m2m100-1.2b

**Resource:** [Workers AI Translation](../resources/Workers-AI-Translation.md)
**Execute @cf/meta/m2m100-1.2b model.**
**Operation ID:** `workers-ai-post-run-cf-meta-m2m100-1-2b`

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
